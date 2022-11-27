# Javascript I - Lab

## Objective: 
In this lab, you will familiarize yourself with Javascript, JS for short, You will write your first JS code by using Input/Output functions, variables, numbers and strings... as well as start grasping the idea of using DOM in JS and having more control over your HTML pages!





<img src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif" width="400">




## Instructions:
> Before we start, make sure to create a new file and call it "js1", it can be in any code editor of your choice.

### Part 1 : User I/O 
 - In the `<script>` tags OR your `.js` file, use `console.log` to print `"I love CS!"` to the console.
 - If you are running your code locally (on Sublime or any other editor): Open the Inspector `(Right Click > Inspect)` in your Browser and look for the Console. 
 - If you are running your code on Repl.it: You should already have your console open.
 - Check to see if `"I love CS!"` was output to the console. If not, refresh and try again.

^ **The console** is where you also can look out for information related to your JS, warnings, errors, requests and more... but we will not be dealing with all of this right now.

### Part 2 : Variables, Numbers, and Strings
 - Use `prompt()` to ask the user for the **year they were born**. Store this value as a `Number` in a variable called `birthYear`.
 - Ask the user for their **lucky number**. Store this value as a `Number` in a variable called `luckyNumber`.
 - Create **two** `String` type variables called `favFruit` and `favSubject`.
   - Example:
   ```javascript
   var favFruit = "Watermelon"
   var favSubject = "CS!"
 - Show the user the answer to the following questions using `alert()`:
   1. What is the value when birthYear is divided by luckyNumber?
   1. What is the value of birthYear + luckyNumber?
   1. What is the value of favFruit + birthYear + luckyNumber + favSubject?
    
> ***Not sure what to do? Try Googling for the following terms:*** javascript alert and prompt, javascript variables.  



### Part 3 : Document Object Model
Also known as the DOM.

- Add an `<h1>` tag in your HTML page, and set its `id` attribute to anything you want.
  -  Example: `<h1 id="title1">Welcome to my page</h1>`
- In your Javascript, add a function that changes the `innerHTML` (which is the text) of the `<h1>` you added in the step 1.
  - Tip: google how to create functions in Javascript!
  - For example: your line would be `document.getElementById("title1").innerHTML = "I control the page now!;`
- Add a `<button>` tag in your HTML page, and set its `onclick` attribute to the function you created in step 2.
  - For example: if your function's name is `changeText`, it would be `<button onclick="changeText()">Next</button>`
- **Fun Bonus:** In the same function you created in step 2, add a line that changes the background color to any color you want!
  - Tip: google how to change the body background color in DOM Javascript.



<img src="https://www.w3schools.com/js/pic_htmltree.gif" width="600"> 



#### Great job!
##### Call an Instructor/TA to check your completed tasks


## Bonus:
#### 1) Write a calculator application, using Javascript!
  - It should have 4 basic calculator functions: Addition (+), Subtraction (-), Multiplication (*), Division (/).
  - Add a menu.
  - The calculator should stop when the user says so. For example: "Exit" word should stop the program.

#### 2) Write a two-player game of Tic-Tac-Toe in JavaScript. The game should do the following:
  - Alternate turns between the two players, prompting each player to enter his or her move as an index from 1 to 9 (for the nine spots on the board).
    - You will need to learn about loops in Javascript. Feel free to research it.
  - When prompting the user for a move, display the current state of the board in the prompt.
  - Check that the player entered a valid move: between 1-9, and only free spaces are allowed.
  - After each move, check to see if a player won, or if the game ended in a draw (neither player won).
  - After the game ends, ask the players if they want to start a new game, and start a new game if they do.
 
**References:**
- JavaScript Numbers: https://www.w3schools.com/jsref/jsref_obj_number.asp
- JavaScript Strings: https://www.w3schools.com/jsref/jsref_obj_string.asp
- JavaScript Errors: https://www.w3schools.com/js/js_errors.asp


<img src="https://media.giphy.com/media/26grMgCg1xZh28AF2/giphy.gif" width="350">
