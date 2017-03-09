---
layout: essay
type: essay
title: Meteor Gotchas
date: 2017-03-09
labels:
 - Software Engineering
 - Meteor
---

## Meteor

Over the past few weeks I've been learning how to use Meteor in one of my Computer Science classes. For those that don't know, Meteor is a Javascript framework that combines both the front-end (part of web app that user sees and interacts with) and back-end (code behind-the-scenes that runs everything). Because of the fact that it does both of these things and there are so many things running behind-the-scenes, it can be quite difficult to learn, especially for beginners who haven't worked on many large projects. I've worked with frameworks before (Qt for C++) and no matter how simple they are, it still takes time to learn all of their different functions and capabilities. I've personally found learning the basics of Meteor more difficult than Qt because there is quite a bit more going on with Meteor. Qt is a C++ framework that allows you to create GUIs, and the basics required there is just learning how to connect a GUI element to a certain piece of your code. With Meteor, you have to design both the part of the web application that everyone sees while also creating and maintaining the database behind it. So far, I haven't run into many mind-boggling bugs in Meteor that I couldn't solve, but I think that is due to the fact that I'm just starting out and am currently just following directions and trying to get as comfortable with Meteor as possible. With that said, there are still a couple of noteworthy problems I ran into.

## Meteor Problems I've Run Into

In the class I'm taking, to learn Meteor we've been working on creating a web application called Digits. Digits is essentially a page full of contacts that the user can add and edit to. We haven't been building it completely from scratch as we are given directions and a picture to replicate. The first problem that comes to mind when I think about replicating this app is when I was working on wiring up the Add Contact page to the database. Essentially, I had incorrectly written the import statement wrong on one line in one file and it pretty much broke the whole app. The list of contacts on the homepage no longer was visible, the add contact page didn't work, and even the header color was gone. And this was all because I had written an import statement wrong. Luckily, I found the line and everything worked properly after that. 