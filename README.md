# Applied JavaScript Sprint Challenge

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past sprint and apply them in a concrete project. This sprint explored **Applied JavaScript**. During this sprint, you studied **DOM and components**. In your challenge this week, you will demonstrate your mastery of these skills by creating **an online Lambda newspaper**.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge.

## Project Set Up

- [ x] Fork and clone the repo. Delete your old fork from Github first if you are repeating this Unit.
- [x] Open the assignment in Canvas and click on the "Set up git" option.
- [ x] Push your first commit: `git commit --allow-empty -m "first commit" && git push`.
- [ x] Check to see that Codegrade has accepted your git submission.

## Project Instructions

### Introduction

You are going to create a Lambda Newspaper. Your job is going to be to create the components that make up the newspaper's home page.

In meeting the minimum viable product (MVP) specifications listed below, your project should look similar to the image linked below:

[Lambda Times](https://tk-assets.lambdaschool.com/cac4803c-6e8f-4846-be0e-b20d82a34a73_lambda-times.png)

### Instructions

- [ x] Navigate to the root of the project with your command line.
- [ x] Run `npm install` to download the dependencies listed in the `package.json` file.
- [x] Run `npm start` to compile the project and serve it.
- [ x] Navigate Chrome to `http://localhost:3000`
- [ x] In a separate terminal, run `npm test` to run tests.

**Steps Required for MVP:**

- [ ] Steps 1 and 2 are explained inside the `src/components/header.js` file.
- [ ] Steps 3 and 4 are explained inside the `src/components/tabs.js` file.
- [ ] Steps 5 and 6 are explained inside the `src/components/card.js` file.

**Important Notes:**

- Please **do not move or rename existing files** or folders.
- If your development server stops "auto reloading", manually kill it with `CTRL+C` and restart it.
- Do not change the `package.json` file except to install libraries with NPM (Axios is _already_ in the `package.json`).
- In your solution, it is essential that you follow best practices and produce clean and professional results.
- Schedule time to review, refine, and polish your work, including spell-checking and grammar-checking.
- It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Submission format

- [ ] Submit via Codegrade by committing and pushing any new changes to the _main_ branch.
- [ ] Check Codegrade for automated feedback.
- [ ] Check Codegrade in the days following the Sprint Challenge for reviewer feedback.
- [ ] Any changes pushed after the deadline will not receive any feedback.

## Interview Questions

Demonstrate your understanding of this week's concepts by answering the following questions:

1. What is the DOM?

   Document object model. A virtual structure representing what will render in the browser in HTML. Javascript interacts with the dom as a representation of the nodes it is affecting.

2. What is an event?

   Any kind of interaction with the browser is an event. Each event is represented by an object that provides a lot of info about what happened and where. This is a part of a system that almost allows Javascript and the web to become self conscious and alive in a sense when combined with listeners.

3. What is an event listener?

   It is a function of the event target interface. It is a method that flows through the DOM in reaction to specific events it is listening for. I like to think of it as a sensor.

4. Why would we convert a NodeList into an Array?

   To be able to use higher order array functions on the data. From my understanding it essentially is an indexed ordered list that can be accessed the same other than being able to use these handy methods on.

5. What is a component?
   A component is a part of a whole. It is encapsulated code that on its own performs a function or purpose. It can be added as a component piece of a larger application and from my understanding it often is with React and applied JS. It makes code reusable, less prone to failure because it isn't being repeated and allows engineers to focus on architecture and functionality vs. being bogged down zombie coding repetitively.
