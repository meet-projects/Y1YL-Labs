# Y1 Yearlong 2022/23 - Session 1, Python Review 1 Lab

## Objective:
During this lab: 
- You will be using Python as a programming language, the lab should help you review python from the Y1 summer, especially variables and conditionals.
- You will be more familiarized with **LOOPS!**






[![](https://i.imgur.com/DfQqM.gif)]()




## Instructions:
> Before we start, make sure to navigate to your team in repl.it and click on "Python Review 1"!

1. In `main.py`,  write a Python code which iterates (goes through) the integers from 1 to 50 using **For loops**.
1. Inside the For loop, apply the following tasks:
	- if the number is a multiple of three: `print("Fizz")`.
	- if the number is a multiple of five: `print("Buzz")`.
	- if the number is a multiple of five **AND** a multiple of three: `print("FizzBuzz")`
	- if none of the above conditions is `true`, just print the number itself.


**Bonus Section below!**
<br>
***Good Job! Remember to show your wonderful work to your Instructors and TAs.***


[![](https://code.kx.com/q/img/fizzbuzz.png)]()

    
  
  
<br>
<br>
<br>
<br>  


## Bonus:
In this part you will create a game called **Nim**:  

#### Game Instructions:
- The game Nim starts out with **seven sticks** on the table.
- Each turn one player picks up 1, 2 or 3 sticks and cannot pass.
- Whoever picks up the last stick loses (the other player wins).
- **Input:** The number of sticks the player is picking up
- **Output:**
	- The number of current sticks on the table.
	- Who won.  


We will build this game with 2 players: **player_a** & **player_b**.

**Follow the following steps:**
1. Print the game instructions to the players
2. Add the following variables to your code:
```python
end_game = False
total_sticks = 7
winner = ""
```
3. Create a `while loop` which will keep running while `end_game` is `False` and **stops** when `end_game` is `True`.
4. In the `while loop` take the number of sticks that **player_A** wants to pick.
	- *Remember: it should be 1 or 2 or 3.*
	- **Hint**: use `player_a_sticks = int(input("Enter a number: "))`
5. Next, **subtract** `player_a_sticks` from the `total_sticks` and **save** the answer back in `total_sticks`.
6. Check if the `total_stick` is equal to **zero** using conditionals.
	- If the `total_stick` is equal to zero then do `winner= "player_b"` and `end_game = True`.
	- If not, print the `total_stick` left on the table, and take a number of sticks from `player_b` using python inputs.
	- Then, **subtract** the number of sticks that `player_b` picked from the `total_sticks`.
	- If the `total_sticks` is equal to **zero**, do `winner=player_a` and `end_game=true` 
	- If not, print the number of `total_sticks` left and **keep looping** until the game ends.
7. When the game ends - outside of the loop **print the winner** (Player a/b). 

    
**Good luck & Do your best!  
Remember to show your brilliant work to your partners and instructors so we can learn from each other.**   
![](https://jeuxsoc.fr/n/nim___01.jpg)


