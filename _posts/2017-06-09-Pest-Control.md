---
layout: post
title: Pest Control

---

# Pest Control: A Systematic Approach to Troubleshooting Bugs

The code should work, right? Everything looks good and with nervous breath, you save and load your page.

And then nothing. A peek at the console shows all manner of angry red error text. You've gone through the code several times at this point, and can't find the error. So you take the only proven method to remove bugs.


![Catharsis!](https://media.giphy.com/media/RhEvCHIeZAZ6E/giphy.gif)


## Preventative Maintenance

The first step to dealing with bugs is on the front, side before you do anything. A large number of errors are self-inflicted. It could be that you are "cowboy coding", launching into a project coding as fast as you can and fixing things on the fly (guilty). Other times it can be geting in the middle of a complicated function and being unable to find your way back out.

![Me in the middle of my code]('https://s-media-cache-ak0.pinimg.com/736x/4c/db/f7/4cdbf7706906e7ab1d2776d73442cd8d.jpg')

A simple, methodical approach can yield huge benefits. A little organization up front will result in fewer bugs and when they do appear, make it easier to troubleshoot. Starting a fresh project I try and follow a set pattern to provide clarity of thought.

1. Drink Coffee
2. Comment my steps
3. Drink some more coffee.

Coffee is self-explanatory, but when I'm staring at a blank file and ready to code, I like to comment my steps before I type anything.

```
// The overall goal
// My first step
// My second step
// My third step
// This should result in
// Output, working program
```

It's rarely that simple, but it's a first check to see if my approach is right. From there, I try and code a simple function to do each thing, until everything has a function. It's also important to keep the scope narrow for each function, and comment it as you go. Each function should have a singular job (process an array, handle a decision point, etc). When to many things add into a function, you open yourself up to problems. Simple functions also mean you can reuse functions more frequently.

As you make your way through your code you should give those bugs fewer places to hide, but those things are crafty, and find their way in anyways.

## So, You've Got an Infestation

Even with the utmost care, you still ended up with a crow's nest of an issue. A simple exercise I use has been pretty beneficial in finding my way out.



In the text editor open a brand new file next two the problematic file. From there, go line by line in your code. If you look at a line and are 100% sure what it does, and how it does it, copy it to the new file. If you aren't sure, leave it. Work through the whole file that way copying known items to the new file. If it doubt, leave it the old file. Once you've finished that, look through both files. Odds are, the bug still in the old file and you can begin to unravel those pieces. You also may look at what's in the new file and see the code in a new light and find a new way through. 

Of course, it may be that you get through all of that and you realize the bug was because you misspelled function somehwere, and then it's back to Plan A.

![Catharsis!](https://media.giphy.com/media/RhEvCHIeZAZ6E/giphy.gif)