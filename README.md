# project-tetris

sample -- extremely simple.
https://torisky.com/games/tetris/v0_7/index.html

1) Take a look at some descriptions of how Tetris works, like https://www.wikihow.com/Play-Tetris -- what variables might you need to save in your program to keep track of the user's progress as they play? How many numbers does the game track and what do they all represent?

#### variables I want to save
- When I see the game board as a grid table, Which blocks are filled (ON).
- the number of lines user deleted.

#### How many numbers does the game track and what do they all represent?



2) How many different user inputs (different events) can happen during the game? (Example of user inputs: clicking the mouse, scrolling, pressing a certain key on the keyboard.)

- clicking the mouse
- pressing the arrow keys on the keyboard
- pressing a space key on the keyboard

3) What are some decisions that the computer needs to make during Tetris? Think about cause and effect, and just make notes on this in plain English, doesn't need to be code yet. Like "if [this happens], then the computer should [do this]."

4) Paper prototyping is something that professional game developers actually do! They cut out pieces of paper and simulate the game they have an idea for by moving around bits of paper along with another friend to help them test it. It might feel silly but it really works!! It helps you get into problem-solving mode and break down the big idea into the little details -- just like what you need to do as a programmer. I say try it! :)

<hr>

3. Outline your first implementation details
Based on what you've learned so far, you can already start digging into how you'll start building the first prototype for your project! In your README.md file, write down some notes based on the following prompts. It's OK if they're just bullet points.

How would you describe the inputs of your app? 
What goes in? What data does your app take in from the user, if any? Will it get data from a databse or from a third-party service?

How would you describe the outputs or possible outcomes of your app? 
Based on those inputs, what does the app display to the user? What are some of the outcomes or results that your app produces based on how the user interacts with it?

What would you store as variables in your JavaScript file for the first prototype of your app? 
What does the computer need to remember between when the user starts the app and when they close the page?

Which kinds of data types are these inputs/variables? 
Are they strings of text? Numbers? Boolean values (true or false)?

<hr>

3/3
http://hangman-v0-final.glitch.me/

https://github.com/LearnTeachCode/intro-javascript-class/blob/march-2018/week-1/1-2-dom-challenges.md

left to right

General to specific

Dot means “look inside of it.”

document.getElementById(“outcome”).textcontent = “test”;

— html download first. Html is a default, canvas. JS add things, cover things.

Variable can be declared once.

“Let” make the space in the memory

<hr>

Notes on our call today: CSS animation, graphics for Tetris

Two main ways to do graphics on the web:
1) Canvas API (draw pixels to a canvas element)
2) Using multiple DOM elements with CSS/JavaScript animation

Suggested resources / tutorials:
- Check out p5js library for easier Canvas animations. They have a good beginner tutorial:
https://p5js.org/get-started/

- Intro to CSS animation with DOM elements, a pretty detailed intro guide:
https://developer.mozilla.org/en-US/docs/Web/CSS/animation

- CSS Animation 101 email course (4 week course, you can do it free or donate to the creator, he sends you a daily email teaching CSS animation in 10-minute mini lessons):
https://cssanimation.rocks/courses/animation-101/

- Can I use website tells you which browsers support features in HTML/CSS/JS:
https://caniuse.com/
   - Example, the "let" statement in JS is well supported: https://caniuse.com/#feat=let
