---
title: Function and Control Tasks Part 2!
description: Learning JavaScript! Again..........
date: 2023-09-30
draft: false
tags:
- posts
- JavaScript
---

I love JavaScript!!! It totally doesn't make me want to rip my hair out!!
Partially joking, don't worry...... Anyway.

So the task was to create a function that is able to return a specific percentage of any number. We got given steps on how to complete this and it took me a lot longer than I'd care to admit.
I started off with the function keyword and then naming it percentageCalculator then defining the parameters.

My first attempt looked like this: 

function percentageCalculator(number, percentage){
const result = (number * percentage) / 100;
return result;
}

percentageCalculator(90,10);


when that didn't work I very stupidly tried:
return percentageCalculator / 100;


I understand my thinking, but I realise that I just wasn't utilizing JavaScript how it's meant to be used, I was just grasping at straws and trying to create something with the limited knowledge that I posess. I wasn't giving it a way to display the result first of all, but I also think I was overcomplicating it. 
My next attempt looked like this:

function percentageCalculator(number, percentage){
return number * percentage / 100;
}

percentageCalculator(90,10);

This is painful to look back at as I was so close, but I was already fried and this was the first task. Thankfully it quickly clicked and I changed the final line to:

console.log(percentageCaluclator(90,10));

This worked finally! It returned 9! And then I tested it with other numbers that were also very easy to work out. I was so relieved, but not for long as there were more tasks to be done!


The next task was learning about switch statements in the form of a drink order output. This was the first time I'd heard of switch statements, and at the time I was hoping it was the last. It took some hard thinking and a freeCodeCamp video to understand them but this still took me less time than the last task. I think because this is actually not difficult code when you exclude the switch statements, and once you do the switch statement, it's just repeating that code for each selection. 
This was my code:

function drinkOrder(size, buttonName){
  let text;
  switch (buttonName) {
    case "Coke":
      text = `${size} Coke.`
      break;
    case "Lemonade":
      text = `${size} Lemonade.`
      break;
    case "Orangeade":
      text = `${size} Orangeade.`
      break;
    default:
      text = `Invalid drink selection.`;
      break;
  }
  console.log(text)
}

drinkOrder("Small", "Coke");
drinkOrder("Medium", "Lemonade");
drinkOrder("Large", "Orangeade");


This task greatly helped me with the next task so although I remember being very braindead by this point I somehow managed to do the task. 

The final task was to create a function capable of using the addition, subtraction, multiply, divider or modulus operator on 2 numbers provided. To do this we used switch statements again and so I came up with this:

function calculator(number1, operator, number2){
  let result;
  
  switch (operator) {
    case '+':
      result = number1 + number2;
      break;
      
    case '-':
      result = number1 - number2;
      break;

    case '*':
      result = number1 * number2;
      break;

    case '/':
      result = number1 / number2;
      break;
    default:
    result = 'Invalid operator';
    break;
}
  console.log(`${number1} ${operator} ${number2} = ${result}`);
  
}
  
  calculator(6, '*', 2);


The two things I forgot to do but quickly resolved was forgetting the final closing bracket, and forgetting to put the operator into quotes. 

Overall, although I felt like I was in hell for a short time, it helped me understand JavaScript a bit better.