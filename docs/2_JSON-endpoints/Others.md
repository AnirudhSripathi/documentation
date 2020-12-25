# Lyrics

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/lyrics`
- **Required parameters:**
    - title - the title of the song you want
- **Required queries:**
    - None
- **Example output:**
```js
{
    title: "Firestone (Ft. Conrad Sewell)",
    author: "Kygo",
    lyrics: "I'm a flame, you're a fire I'm the dark in need of light When we touch, you inspire Feel it changin' me tonight Take me up, take me higher There's a world not far from here We can dance in desire Or we can burn in love tonight Our hearts are like firestones And when they strike, we feel the love Sparks will fly, they ignite our bones And when they strike, we light up the world Our hearts are like firestones And when they strike, we feel the love Sparks will fly, they ignite our bones And when they strike, we light up the world We light up the world We light up the world Whoa, oh World Whoa, oh Firestone I'm from X You're from Y Perfect strangers in the night Here we are, come together To the world we'll testify Our hearts are like firestones And when they strike, we feel the love Sparks will fly, they ignite our bones And when they strike, we light up the world Our hearts are like firestones And when they strike, we feel the love Sparks will fly, they ignite our bones And when they strike, we light up the world We light up the world We light up the word Whoa, oh World Whoa, oh Firestone",
    thumbnail: {
        genius: "https://images.genius.com/cb89269cd3f9f4bbf86c1563fc5cb1d3.300x300x1.jpg"
    },
    links: {
        genius: "https://genius.com/Kygo-firestone-lyrics"
    },
}
```

# Meme

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/meme`
- **Required parameters:**
    - title - the title of the song you want
- **Required queries:**
    - None
- **Example output:**
```js
{
  id: 9,
  image: "https://i.some-random-api.ml/WbL79WnQh0.png",
  caption: "Every pvp strategy",
  category: "anime"
}
```

# Base64

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/base64`
- **Required parameters:**
    - None
- **Required queries:** (choose one)
    - decode
    - encode
- **Example output:**
```js
{
  base64: "aGVsbG8="
}
```

# Binary

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/binary`
- **Required parameters:**
    - None
- **Required queries:** (choose one)
    - decode
    - text
- **Example output:**
```js
{
binary: "0110100001100101011011000110110001101111"
}
```

# Joke

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/joke`
- **Required parameters:**
    - None
- **Required queries:**
    - None
- **Example output:**
```js
{
  joke: "I was struggling to figure out how lightning works then it struck me."
}
```

# Minecraft

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/mc`
- **Required parameters:**
    - username - Mc username
- **Required queries:**
    - None
- **Example output:**
```js
{
  username: "G8Nerd",
  uuid: "5da80f2bcbe04b9c89feffa13bf29240",
  name_history: [
    {
      name: "G8Nerd",
      changedToAt: "Original Name"
    }
  ]
}
```

