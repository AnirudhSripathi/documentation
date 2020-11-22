# Animu gifs

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/animu/:category`
- **Required parameters:**
    - category - The type of gif you want 
- **Required queries:**
    - None
- **Example output:**
```js
{
    "link": "https://i.some-random-api.ml/pHJ6jx0kLl.gif"
}
```

## List of valid endpoints
- wink
- pat
- hug
- face-palm

## Code Examples
```js
const fetch = require('node-fetch')

fetch('https://some-random-api.ml/animu/hug')
    .then(res => res.json())
    .then(json => console.log(json));
```

# Anime quotes

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/animu/quote`
- **Required parameters:**
    - None
- **Required queries:**
    - None
- **Example output:**
```js
{
    "sentence": "Some quote some person said",
    "characther": "that some person",
    "anime": "the anime they exist in",
}
```

## Code Examples
```js
const fetch = require('node-fetch')

fetch('https://some-random-api.ml/animu/quote')
    .then(res => res.json())
    .then(json => console.log(json));
```