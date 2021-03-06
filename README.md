# Javascript
## for, while, do...while() Loop

* Write a loop which prompts for a number greater than 100. If the visitor enters another number – ask him to input again. The loop must ask for a number until either the visitor enters a number greater than 100 or cancels the input/enters an empty line. Here we can assume that the visitor only inputs numbers. There’s no need to implement a special handling for a non-numeric input in this task.

* An integer number greater than 1 is called a prime if it cannot be divided without a remainder by anything except 1 and itself.In other  words, n > 1 is a prime if it can’t be evenly divided by anything except 1 and n.For example, 5 is a prime, because it cannot be divided  without a remainder by 2, 3 and 4. Write the code which outputs prime numbers in the interval from 2 to n. For n = 10 the result will be 2,3,5,7 .P.S. The code should work for any n, not be hard-tuned for any fixed value.

* For every loop, write down which values it shows, in your opinion. And then compare with the answer. Both loops alert same values or not?
The prefix form ++i: 
```javascript
let i = 0;
while (++i < 5) alert( i );
The postfix form i++
let i = 0;
while (i++ < 5) alert( i );
```
* For each loop write down which values it is going to show. Then compare with the answer. Both loops alert same values or not?
The postfix form:

```javascript
for (let i = 0; i < 5; i++) alert( i );
The prefix form:
for (let i = 0; i < 5; ++i) alert( i );
```

## obiect
* Write the function isEmpty(obj) which returns true if the object has no properties, false otherwise.
Should work like that:
```javascript
let schedule = {};
alert( isEmpty(schedule) ); // true
schedule["8:30"] = "get up";
alert( isEmpty(schedule) ); // false
```

* Create a function multiplyNumeric(obj) that multiplies all numeric properties of obj by 2.
For instance:
```javascript
// before the call
let menu = {
  width: 200,
  height: 300,
  title: "My menu"
};

multiplyNumeric(menu);

// after the call
menu = {
  width: 400,
  height: 600,
  title: "My menu"
};
```
