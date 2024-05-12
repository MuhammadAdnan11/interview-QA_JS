# interview-QA_JS
## Follow me and give Stars⭐⭐, if you like these contents and wanna further in the future...✅❤

### Which one is generally better, line 1 or line 2?
```
let empty1 = undefined; //line 1
let empty2 = null; //line 2
```

### What will be logged to the console?
```

let a = "world";
let b = `Hello ${a}!`;
console.log(b);
```

### What is the value of a?
```

let a = "Hello";
a = prompt("world");
console.log(a);
```

### What is the value of total and total2?
```

let firstNum = 5;
let secondNum = 10;
firstNum++;
secondNum--;
let total = ++firstNum + secondNum;
console.log(total);
let total2 = 500 + 100 / 5 + total--;
console.log(total2);
```

### What is logged to the console here?
```
const a = 5;
const b = 10;
console.log(a > 0 && b > 0);
console.log(a == 5 && b == 4);
console.log(true ||false);
console.log(a == 3 || b == 10);
console.log(a == 3 || b == 7);
```
### What will be the output?
```
1. Create an array to use as your shopping list with 3 items: "Milk," "Bread," and
"Apples."
2. Check your list length in the console.
3. Update "Bread" to "Bananas."
4. Output your entire list to the console.
```

### Take out the street value of second object in the array...
```
let addresses = [{
street: "2nd street",
number: "123",
zipcode: "33116",
city: "Miami",
state: "Florida"
},
{
street: "1st West avenue",
number: "5",
zipcode: "75001",
city: "Addison",
state: "Texas"
}];

```

### Output ..
```
1. Create an object named people that contains an empty array that is called
friends.
2. Create three variables, each containing an object, that contain one of your
friend's first names, last names, and an ID value.
3. Add the three friends to the friend array.
4. Output it to the console.
```

### What is the output in the console?
```

const myArr1 = [1,3,5,6,8,9,15];
console.log(myArr1.indexOf(0));
console.log(myArr1.indexOf(3));
```

### What is the output in the console?
```

const myArr3 = [3,6,8,9,3,55,553,434];
myArr3.sort();
myArr3.length = 0;
console.log(myArr3[0]);
```

###  Output the response message variable to the console
```
1. Create a prompt to ask the user's age
2. Convert the response from the prompt to a number
3. Declare a message variable that you will use to hold the console message for
the user
4. If the input age is equal to or greater than 21, set the message variable to
confirm entry to a venue and the ability to purchase alcohol
5. If the input age is equal to or greater than 19, set the message variable to
confirm entry to the venue but deny the purchase of alcohol
6. Provide a default else statement to set the message variable to deny entry if
none are true
7. Output the response message variable to the console
```

### In this exercise, we'll create a Magic 8-Ball random answer generator:
``
1. Start by setting a variable that gets a random value assigned to it. The value
is assigned by generating a random number 0-5, for 6 possible results. You
can increase this number as you add more results.
2. Create a prompt that can get a string value input from a user that you can
repeat back in the final output.
3. Create 6 responses using the switch statement, each assigned to a different
value from the random number generator.
4. Create a variable to hold the end response, which should be a sentence
printed for the user. You can assign different string values for each case,
assigning new values depending on the results from the random value.
5. Output the user's original question, plus the randomly selected case
response, to the console after the user enters their question.`

```
