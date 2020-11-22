# Animal Faxxs

## Endpoint Information
- **Method:** GET
- **URL:** `https://some-random-api.ml/facts/:animal`
- **Required parameters:**
    - Animal - the animal you want
- **Required queries:**
    - None
- **Example output:**
```js
{
    "fact": "animal stinky"
}
```

## List of valid endpoints
- Dog
- Cat 
- Panda
- Fox
- Birb
- Koala
- Kangaroo
- Racoon
- elephant
- giraffe
- whale

## Code examples
```js
const fetch = require('node-fetch')

fetch('https://some-random-api.ml/facts/panda')
    .then(res => res.json())
    .then(json => console.log(json));
```