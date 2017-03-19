![Lethal Weapon 5](https://raw.githubusercontent.com/moe-szyslak/Lethal-Weapon-5/master/Lethal-Weapon-5.png "Lethal Weapon 5")

Rotten Tomatoes scraper using their private search API - no API key needed

## Installation
`npm install lw5` or `yarn add lw5`

## Usage
```javascript
const lw5 = require('lw5');

const bestMovieEver = await lw5('Lethal Weapon 5', 2005, 2015); // looks for movie 'Lethal Weapon 5' between 2005 and 2015 [inclusive]
```
