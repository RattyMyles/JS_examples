# Variables

The ```let``` keyword signals that the variable can be reassigned a different value.
```let``` can declare a variable without assigning the variable a value. In such a case,
the variable will be automatically initialized with a value of undefined.

```
let xbox_game = 'Halo 3';
console.log(xbox_game); // Output: Halo 3
let xbox_game_2;
console.log(xbox_game_2); // Output: undefined
xbox_game_2 = "Gears of war";
console.log(xbox_game_2); // Output: Gears of war
```

a ```const``` variable cannot be reassigned because it is constant.
If you try to reassign a const variable, you’ll get a TypeError.

```
const game = "FarCry"
console.log(game) // Output: FarCry
game = "Call of duty" // Output: TypeError
```
