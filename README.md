# Javascript
## for, while, do...while() Loop

1. Write a loop which prompts for a number greater than 100. If the visitor enters another number – ask him to input again. The loop must ask for a number until either the visitor enters a number greater than 100 or cancels the input/enters an empty line. Here we can assume that the visitor only inputs numbers. There’s no need to implement a special handling for a non-numeric input in this task.
```javascript
let x = prompt("please enter a number",'');
let inputValue = +x;

while ( (inputValue <= 100) && (inputValue != 0) ) {
    let y = prompt("please enter a number",'');
    let inputValue = +y;
}
```

1. An integer number greater than 1 is called a prime if it cannot be divided without a remainder by anything except 1 and itself.In other  words, n > 1 is a prime if it can’t be evenly divided by anything except 1 and n.For example, 5 is a prime, because it cannot be divided  without a remainder by 2, 3 and 4. Write the code which outputs prime numbers in the interval from 2 to n. For n = 10 the result will be 2,3,5,7 .P.S. The code should work for any n, not be hard-tuned for any fixed value.
```javascript
let n = 10;

for (i = 2; i <= n; i++) {
    if (n % i == 0) {
       // how to output each n?
    }
}
```
