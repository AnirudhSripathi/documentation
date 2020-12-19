# Overlays

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/canvas/:overlay`
- **Required parameters:**
    - overlay - The overlay you want
- **Required queries:**
    - avatar - Direct link to the image you want
- **Example output:**

![Output Example](https://some-random-api.ml/canvas/wasted?avatar=https://cdn.discordapp.com/avatars/423675224395874314/fabb76c56faae70a2d61caaf73af723c.png)


## List of valid endpoints
- gay
- glass
- wasted

## Code examples
```js
const { MessageEmbed, MessageAttachment } = require('discord.js')

let link = `https://some-random-api.ml/canvas/wasted/?avatar=${message.author.avatarURL({ format: 'png'})}`

// -------- Sending the image as an image attachment --------
//create a message attachment with the name of the file with discord.js built in attachment class.
let attachment = new MessageAttachment(link, 'wasted.png');
message.channel.send(attachment); //send the attachment

// -------- Sending the image inside an embed --------
const attachment = new MessageAttachment(link, 'wasted.png');
  const embed = new MessageEmbed()
    .setTitle(`Image Generated?`)
    .attachFiles(attachment)
    .setImage('attachment://wasted.png')
  message.channel.send(embed);
```