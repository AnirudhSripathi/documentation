# Triggered endpoint

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/canvas/triggered`
- **Required parameters:**
    - None
- **Required queries:**
    - avatar - Direct link to the image you want
- **Example output:**

![Output Example](https://some-random-api.ml/canvas/triggered?avatar=https://cdn.discordapp.com/avatars/423675224395874314/fabb76c56faae70a2d61caaf73af723c.png)

## Code examples
```js
const { MessageEmbed, MessageAttachment } = require('discord.js')

let link = `https://some-random-api.ml/canvas/wasted/?avatar=${message.author.avatarURL({ format: 'png'})}`

// -------- Sending the image as an image attachment --------
//create a message attachment with the name of the file with discord.js built in attachment class.
let attachment = new MessageAttachment(link, 'triggered.gif');
message.channel.send(attachment); //send the attachment

// -------- Sending the image inside an embed --------
const attachment = new MessageAttachment(link, 'triggered.gif');
  const embed = new MessageEmbed()
    .setTitle(`Image Generated?`)
    .attachFiles(attachment)
    .setImage('attachment://triggered.gif')
  message.channel.send(embed);
```

# Petpet endpoint

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/canvas/petpet`
- **Required parameters:**
    - None
- **Required queries:**
    - avatar - Direct link to the image you want
- **Example output:**

![Output Example](https://some-random-api.ml/canvas/petpet?avatar=https://cdn.discordapp.com/avatars/423675224395874314/fabb76c56faae70a2d61caaf73af723c.png)