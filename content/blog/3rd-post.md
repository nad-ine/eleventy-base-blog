---
title: Function and Control Tasks
description: Learning JavaScript!
date: 2023-09-28
draft: false
tags:
- posts
- JavaScript
---

This was working with the function keyword, which thankfully my brain has managed to get the hang of, little can be said about what's to come. I know eventually I'll get it but until then I've just got to remember what things do. Anyway, this task involved creating a function by defining the function with the name, then creating the function parameters. Mine were very simple:

function catFact (fact) {
}

I then asked the console log to show the cat fact in a way where I could change the fact.

console.log('Cats' + fact);

I then called back to the catFact to add the fact that I wanted it to show. Altogether this is how it looked.

function catFact (fact) {
  console.log('Cats' + fact);
}

catFact(" sleep a lot as they have a high protein diet.");


Our next task involved using function to understand the parameter order of the function keyword, we did this by creating a fullName function that would show in the console log.

function fullName(firstName, lastName){
  console.log(`My name is ${firstName} ${lastName}`)
}

fullName("Nadine", "Roberts")

We played around with this by switching the names around and saw how it would display in the order that you put it in. 
The next task we did was very similar except we added the use of const and calling back to the original function for an added name.

function fullName(firstName, lastName){
  return `My name is ${firstName} ${lastName}`
}

const myName = fullName("Nadine", "Roberts")

console.log(myName);
console.log(fullName('Steve', 'Marks'));


The final task was to create JavaScript that could tell you what to wear or if to stay inside depending on the temperature outside. It consisted of conditional statements which was very new to me, I can't say I have a full understanding of conditional statements yet, but this exercise helped me greatly.

const temperature = -10;
const ownAHat = true;

if(temperature < 0 && ownAHat){
  console.log("Stay inside!")
} else if (temperature < 30){
  console.log("Wear a coat and hat!")
} else if (temperature < 50){
  console.log("Wear a coat!")
} else {
  console.log("You're good to go!")
}

Thankfully this final task we got to do in class, because I struggled a lot. It was a few steps above what I was capable of at the time but looking back on it, it makes sense, so it's fun to see my progress in real time like this.