---
layout: project
type: project
image: images/qt-project.png
title: Learning Qt
permalink: projects/learning-qt
date: 2016
labels:
 - C++
 - Qt Framework
summary: This is a summary of my ongoing attempts to improve my programming/C++ skills and learn Qt.
---

## Motivation to Learn Qt

Ever since I started the CS program at UH Manoa, one thing has been very clear. To have a chance of getting a job once you graduate you need projects in your portfolio outside of schoolwork. To be frank I haven't done the best in this respect, but did make some progress during the previous winter break (2016). During the Fall 2016 semester I had just learned C++, and since this is a very feature-rich and complex language I wanted to deepen my knowledge of it. The first idea that popped into my head was to turn the C++ project I had completed in this class, which was an account database driven by a command-line interface, into one with a GUI.

## Qt Roadblocks

As the heading above suggests, I ran into some roadblocks. First off, all of the good tutorials and books I could find were pretty old by programming standards (the youtube videos I used were 5 years old), but it all turned out fine in the end as the person making the tutorials I used was good at explaining concepts and everything in those videos still held true. Since I was still pretty new to C++ and this was my first time working with any sort of framework, I quickly realised that I would learn more efficiently and with less frustration if I took baby steps and eased myself into it. So instead of converting my whole project which would require a ton of input and output with scrolling windows, I decided to make smaller projects for Qt from scratch. 

## Walk Before You Run

The first project I decided to make was the first homework assignment we did in the class where I learned C and C++, which was a temperature conversion program. In the first design for this program it had a separate input and output window, two radio buttons that corresponded to the inputted temperature, and a big button that said convert. With the tutorials I was able to learn about signals and slots, which allow the various GUI objects to interact with each other and is essential to making anything with Qt. As with anything it was difficult starting out, but I eventually got the hang of it. After the program was fully functioning though, I realised that my UI design was poor and pretty confusing. Visual design has never been my strongsuit, so I looked at other similar programs for inspiration and my final design for this temperature conversion program consisted of two input boxes that corresponded to fahrenheit and celsius and would automatically update and convert the opposite temperature of the one you inputted. It was a very small project, but allowed me to learn essential parts of Qt and how to work with the framework. I am now in the middle of my original idea which was to convert the project, but still have a ways to go with it. While converting the program, I had to accomplish things like learning how to make a Qt object read only for output and making the output window scroll. I'm still struggling a little bit with signals and slots and making each element of the GUI interact with each other the way I want them to, but I'm finding it more satisfying than frustrating. When I finish this, I want to make a capital city quiz program built from scratch that uses Qt.
