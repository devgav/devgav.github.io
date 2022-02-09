---
layout: essay
type: essay
title: Dreaming Lint
# All dates must be YYYY-MM-DD format!
date: 2022-02-08
labels:
- Software Engineering
- Learning
- ESLint
---

## Sleeping on Coding Standards
When I first began programming, I did not care much about coding standards. I was more concerned with getting the program to run and compile before submitting it, rather than with how presentable my code looked.However, as my journey as a software engineer continued, I did start to see some benefit in using coding standards and even began to develop some best practices while writing my own code. I think that coding standards can be an underrated part of a project that no one truly appreciates till they begin working with others. Everyone has their own unique style of writing code, and enforcing coding standards just makes working with code that much less frustrating.

## A Nightmare
My initial experience with ESLint was that it was a bit harder to get set up. For some reason, it was just a hassle to get ESLint working on IntelliJ, and it ultimately took me an hour to debug what was going on. I should add that ESLint can be distracting at times because you could be spending hours trying to fix a trivial ESLint error when you could have been working on getting your code working instead. Personally, I prefer to finish whatever problem I am solving and then start to make it look pretty by simplifying the code and then fixing my code to conform to coding standards. This way, I don’t get distracted by fixing those little ESLint errors. Also, ESLint makes a red squiggly under your code, which looks annoyingly similar to a syntactical error that you may get, and it may become difficult to distinguish between the two.

After I had gotten ESLint set up, it immediately exposed all my flaws in programming that I didn't even know I had. For example, in JavaScript, I use "let" to assign every single variable that I create and never found a use for "const". That is until ESLint started correcting me and showing me which areas of my code I could be using the keyword "const". This was definitely very eye-opening to me because if I had not known this, I would have just defaulted to using the "let" keyword for most of my JavaScript career.

## One Team One Dream
If you are working with more than one person, then there may actually be some benefit to setting up some coding standards. Coding standards can help a team help each other by making coding reviews by senior engineers quicker and easier. In turn, this allows your changes to be pushed faster and quicker. In fact, in my project for UHGroupings, we use various tools to keep coding standards within our project, such as Codacy and ESLint. As a new developer, it made reading code much easier because it made a project that had been worked on by 30 different developers over the previous couple of years appear to have been written by only one person. However, I should note that some coding standards can be quite annoying to deal with and even cause delays in important bug fixes that need to be pushed out. Overall, coding standards make large projects that were written by multiple people look like they were written by only one, and they allow teams to collaborate on a project much more easily.

## Linting Alone
While writing this piece, I will admit that I had trouble understanding why one would ever want to use coding standards for their own personal projects. After all, it’s just for you to look at anyway. Additionally, setting up the coding standards is one extra step that you will have to remember before you start your exciting new project. However, as I started looking for a reason, I began looking through some of my past coding projects and realized that some were much harder to look at now that I have been coding for a year. Some lines were not indented correctly, others did not have any spacing, and some were littered with comments, which made the actual code difficult to look at. Also, I learned that when you share your code on GitHub, other developers and potential employers can see all your awful formatting since GitHub does not auto format the code when you push. All of this made me wish I had taken the time to set up some coding standards at the beginning of my project, especially when I first learned to code. It also would have helped me pick up better habits at the beginning of coding.

## Waking Up
Coding standards are something that I think most developers will continue to overlook in their programming career. Mostly because it isn’t as cool as creating the next big program that’ll revolutionize the world, but it is one of those things that makes sure your code can be maintainable and easy to read in case it does ever get happen. And if your future self ever looks back on some older projects, I'm sure they'll thank you for enforcing coding standards from the start.


