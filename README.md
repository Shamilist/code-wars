# Решение задач на code-wars, JS
Профиль https://www.codewars.com/users/Shamilist

## Задача:
Write a function that takes an integer as input, and returns the number of bits that are equal to one in the binary representation of that number. You can guarantee that input is non-negative. <br>
Example: The binary representation of 1234 is 10011010010, so the function should return 5 in this case.
## Решение:
``` JavaScript
var countBits = function(n) {
let binary = n.toString(2).match(/1/g); 
  if (binary) { 
    return binary.length; 
  }
  return 0; // если 0 
};
```
