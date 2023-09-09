# "Random" JS Library
```js
// set a name for Random library (optional)
let myPreferedName = Random;


/* get random integer */
let myInt = Random.int(1, 100); // random integer in range from 1 to 100


/* get random float */
let myFloat = Random.float(1.01, 100); // random floating number from 1.01 to 100


/* get random item from an array */
let weather = ['rainy', 'snowy', 'sunny'];

let todayWeather = Random.choice(weather); // rainy | snowy | sunny


/* shuffle an array */
let cards = ['queen', 'king', 'ace'];

let shuffledCards = Random.shuffle(cards); // all possible variations of array items placed
```
