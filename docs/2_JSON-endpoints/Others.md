# Animal endpoints

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/animal/:animal`
- **Required parameters:**
    - Animal - the animal you want
- **Required queries:**
    - None
- **Example output:**
```js
{
    "image": "direct url to the image",
    "fact": "animal stinky"
}
```

## List of valid endpoints
- dog
- cat
- panda 
- fox
- red panda (use red_panda)
- koala
- birb (this is not a typo)
- racoon
- kangaroo

## Code examples
```js
const fetch = require('node-fetch')

fetch('https://some-random-api.ml/animal/panda')
    .then(res => res.json())
    .then(json => console.log(json));
```