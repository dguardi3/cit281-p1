# cit281-lab1

# Lab 1: Introduction To Terminal and Node.js

### Overview
This lab focused on setting up a computer with the basic software required to launch a Node.js server. From this lab I learned how to use terminal and shell commands to create and manipulate directories, and also how to set up my first Node.js server.

### Project Code
```markdown
/*
    CIT 281 Project 1
    Name: Devin Guardino
*/

// Returns a random number between min (inclusive) and max (exclusive)
function getRandomInteger(min, max) {
    return Math.floor(Math.random() * (max - min) + min);
}

const alphabet = "abcdefghijklmnopqrstuvwxyz".split("");
let result = "";

for (let i = 0; i < getRandomInteger(5, 26); i++) {
    result += alphabet[getRandomInteger(1,alphabet.length-1)];
}

console.log(result);
```

```markdown
const date = new Date();
const days= ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];

console.log(days[date.getDay()]);
```
