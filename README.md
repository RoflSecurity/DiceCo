# dice-coefficient

Sørensen–Dice coefficient for strings, with CLI and Node.js export.

## Usage CLI
dice-coefficient "string1" "string2" [--raw|-r] [--percent|-p]

## Usage Node.js
const { diceCoefficient } = require('dice-coefficient');
console.log(diceCoefficient("Context","Contact"));
