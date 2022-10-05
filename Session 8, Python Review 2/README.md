# Y1 Yearlong 2022/23 - Python Review 2 Lab

## Objective: 
During this lab: 
- You will review python Lists and Functions.
- You will be more familiarized with python Dictionaries!
- You will be creating a mysterious Caesar cipher code and send secret messages!




<img src="https://camo.githubusercontent.com/fe4ba137f41af32ee3004e8d9e5a3bec90b5a7f92b8706a90d5aa51a8c66f940/68747470733a2f2f696a6f7368736d6974682e66696c65732e776f726470726573732e636f6d2f323031352f30342f6361657361722e676966" width="400">




## Instructions:
> Before we start, make sure to navigate to your team on Repl.it and start with lab "2- Python Review 2"!

### Part 1: 
In `main.py` -
1. Add a list to your code and call it `favorite_food`.  
  - Add your top 5 favorite foods to your list.
1. Print the `favorite_food` to the user and take his favorite food using python inputs.
  - Add the user's favorite food to the `favorite_food` list using `.append()`.
1. Ask the user about his **least favorite food** in the list and delete it using `.remove()`.
1. Finally, print the new list.  

**Good Job! Remember to show your wonderful work to your Instructors and TAs.**

### Part 2: 
In cryptography, the easiest form of a cipher is known as a **[Caesar cipher](https://en.wikipedia.org/wiki/Caesar_cipher)**.  
In a Caesar cipher, we encode letters by ***shifting*** the characters in the **alphabet** by some `value` (usually by `3`).  
Here is a Python dictionary that represents the full encoder mapping used in a Caesar cipher.  
```python
encoder_caesar = {'a':'d','b':'e','c':'f','d':'g','e':'h','f':'i','g':'j','h':'k','i':'l','j':'m','k':'n','l':'o','m':'p','n':'q','o':'r','p':'s','q':'t','r':'u','s':'v','t':'w','u':'x','v':'y','w':'z','x':'a','y':'b','z':'c'}
```

1. Add this dictionary to your code.
2. Write a **function** that takes a `string` as a parameter and returns the same string but shifted by 3 letters - according to the Ceasar cipher. 
  - Use the encoder_caesar dictionary.
  - Example: `"meet"` - should be returned as `"phhw"`.
  - *Hint:* check how to print the value of a specific key in a python dictionary.


##### Great job!
##### Call an Instructor/TA to check your completed tasks
 
 


## Bonus:
According to Wikipedia: In **number theory**, a **perfect** number is a positive integer that is equal to the sum/total of its proper positive divisors.  
  
**Example :** 
- The first perfect number is 6, because 1, 2, and 3 are its proper positive divisors, and `1 + 2 + 3 = 6`. 
- The next perfect number is `28 = 1 + 2 + 4 + 7 + 14`. This is followed by the perfect numbers `496` and `8128`.  
  
  
1. Write a Python function to check whether a number is perfect or not if yes the function returns True, if no the function returns False.
 
1. If the number is a perfect number write another function that will return a list of the numbers’ proper positive divisors.

1. if false write another function that will return a string saying “The number is not perfect.”

**Good Job! Remember to show your Brilliant work to your Instructors and TAs.**



<img src="https://i.stack.imgur.com/D3ypD.gif" width="350">
