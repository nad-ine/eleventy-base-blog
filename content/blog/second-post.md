---
title: Learning JavaScript 1
description: Creating a tip programme.
date: 2023-08-25
draft: false
tags:
- posts
- JavaScript
---

I find JavaScript as brain-melting as I find maths, except I liked alebra and it does also have similarities to that.

To create my tip programme which calculate and outputs the tip total, I used this code:

const preTip = 73.43;
const tipPercent = 10;
const tip = preTip * tipPercent / 100;
const total = Number((preTip + tip).toFixed(2));

console.log(`Your total is £ ${total}`);
document.write(`Your total is £${total}`);

It outputted this message: Your total is £80.77


On Moodle, it said to make a procedural function in Javascript, which I don't know what that means, but I wanted to see if I could do it. From my understanding, it's a function that you can use for various tasks, in this case we're using it to calculate and log the total.


function calculateTotal(preTip, tipPercent) {
  const tip = preTip * tipPercent / 100;
  const total = preTip + tip;

console.log(`Your total is £ ${total}`);
document.write(`Your total is £${total.toFixed(2)}`);
}

calculateTotal(73.43, 10);


I understand that order and consistency is very important, especially with JavaScript. Although the first way was a lot simpler, I know the second one is more efficient.