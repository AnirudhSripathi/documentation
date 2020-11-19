# Pokedex
---------------------------------------

__Links__
* [Endpoint](https://some-random-api.ml/pokedex?pokemon=pikachu)

__Example Response__ 
```js
{
  name: "pikachu",
  id: "025",
  type: [
    "Electric"
  ],
  species: [
    "Mouse",
    "Pokémon",
  ],
  abilities: [
    "Static",
    "Lightning Rod",
  ],
  height: "1′04″ (0.4 m)",
  weight: "13.2 lbs (6.0 kg)",
  base_experience: "112",
  gender: [
    "50% male",
    "50% female",
  ],
  egg_groups: [
    "Fairy",
    "Field",
  ],
  stats: {
    hp: "35",
    attack: "55",
    defense: "40",
    sp_atk: "50",
    sp_def: "50",
    speed: "90",
    total: "320",
  },
  family: {
    evolutionStage: 2,
    evolutionLine: [
      "Pichu",
      "Pikachu",
      "Raichu",
      "Raichu",
    ],
  },
  sprites: {
    normal: "http://i.some-random-api.ml/pokemon/pikachu.png",
    animated: "http://i.some-random-api.ml/pokemon/pikachu.gif",
  },
  description: "When several of these Pokémon gather, their electricity could build and cause lightning storms.",
  generation: "1",
}
```