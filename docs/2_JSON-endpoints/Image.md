# Animal endpoints

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/img/:category`
- **Required parameters:**
    - Animal - the animal you want
- **Required queries:**
    - None
- **Example output:**
```js
{
    "link": "direct url to the image",
}
```

## List of valid categories
- dog
- cat
- panda 
- fox
- red panda (use red_panda)
- koala
- birb (this is not a typo)
- racoon
- kangaroo
- whale
- pikachu

## Code examples
```js
const fetch = require('node-fetch')

fetch('https://some-random-api.ml/img/panda')
    .then(res => res.json())
    .then(json => console.log(json));
```