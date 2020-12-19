# Youtube comment

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/canvas/youtube-comment`
- **Required parameters:**
    - None
- **Required queries:**
    - avatar - Direct link to the image you want
    - username - maximum 25 characters
    - comment - maximum 1000 characters
- **Example output:**

![Output Example](https://some-random-api.ml/canvas/youtube-comment?avatar=https://cdn.discordapp.com/avatars/423675224395874314/fabb76c56faae70a2d61caaf73af723c.png&username=Telk&comment=Docs%20are%20cool)

# Color viewer

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/canvas/colorviewer`
- **Required parameters:**
    - None
- **Required queries:**
    - hex - the hex color code without `#`
- **Example output:**

![Output Example](https://some-random-api.ml/canvas/colorviewer?hex=7289DA)


# Hex

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/canvas/hex`
- **Required parameters:**
    - None
- **Required queries:**
    - rgb - an rgb splitted with `,` ex. `255,255,255`
- **Example output:**
```js
{
  hex: "#ffffff"
}
```

# Rgb

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/canvas/rgb`
- **Required parameters:**
    - None
- **Required queries:**
    - hex - Hex string without the `#`
- **Example output:**
```js
{
  r: 255,
  g: 255,
  b: 255
}
```