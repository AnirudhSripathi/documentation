# Chatbot

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/chatbot`
- **Required parameters:**
    - None
- **Required queries:**
    - message - The message you want to talk to the chatbot
    - key - The api key (optional)
- **Example output:**
```js
{
    "response": "Hello little child"
}
```

## Code Examples
```js
const fetch = require('node-fetch')
let message = 'hello'

fetch('https://some-random-api.ml/chatbot?message=' + encodeURIComponent(message))
    .then(res => res.json())
    .then(json => console.log(json));
```