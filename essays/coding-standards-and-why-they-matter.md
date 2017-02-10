---
layout: essay
type: essay
title: Coding Standards and Why they Matter
date: 2017-02-09
labels:
 - Coding Standards
 - ESLint
---

## Coding Standards

The next time you read a book or paper, try to take note of its style. When I refer to style, I'm talking about aspects that range from what perspective it is being written in to the criteria a writer uses to start a new paragraph. Any writing worth its salt will follow some sort of style guide, and this has the effect of making it easy to read and not confusing in any way. When you're reading something, most of the time the style of the writing never enters your head, and I believe this is due to it following a consistent style. When the style is inconsistent, however, you do notice it. For example, if the perspective of a text is constantly changing it can be very offputting and confusing.

Coding is very much the same way. A piece of code can by syntactically correct like a sentence could be grammatically correct, but that doesn't automatically mean that it fits into the piece as a whole. And just like a proper and consistent writing style for a book can make it more readable, the same goes for all the code in a program. Being able to write code is one thing, but being able to write code that is readable and readily understandable to someone else is a whole different ballpark. Most programs are written by multiple people, and if these programs are gonna be efficiently worked on and improved then everybody needs to be able to read everyone else's code. Reading someone's code is a skill in and of itself that takes a lot of practice, but there is an onus on the creator of a piece of code to make it as easy as possible for the people that will have to work with it. There is a lot to writing readable code, from making function and variable names descriptive to keeping functions short and simple, but coding standards and style also play a big part in it. It is already difficult to jump into and work on a large, pre-existing project, and lack of standards will just add to an already overwhelming task.

## ESLint

<img class="ui medium right spaced image" src="../images/eslint.png">

While having some standard guidelines is great, if you can't thoroughly enforce them then there isn't much point. Thankfully we live in great and advanced times, and there are tools out there we can use to enforce these standards. First off, we have IDEs (Integrated Development Environment), which come with great features like code completion, automatic compilers, and incorrect syntax detection. In addition to this are linters, which can detect code that doesn't follow a certain set of (customizable) guidelines, but is syntactically correct. 

For the computer science class that I'm writing this paper for, we've been learning Javascript and have been using ESLint with the AirBnB Javascript style guide. To continue with the writing comparisons, as you continue to program you develop a certain programming style much like you do with writing. Because of this, I was initially frustrated with ESLint as I had to change the way I wrote certain code. For example, 'i++' and 'i += 1' mean the same thing, but I'm used to doing it the former way, and the linter wanted me to always use the latter. However, I quickly got over it and took it as a learning experience. Firstly, the style guide had valid reasons as to why they preferred the code a certain way. Secondly, whenever you start contributing to an already existing project, the chance that the code will follow your own style exactly is very low. You need to be able to adapt, in the name of readability.