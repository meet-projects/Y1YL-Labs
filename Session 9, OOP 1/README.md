# Y1 Yearlong 2023/24 - OOP Lab


## Objective: 
During this lab, you will familiarize yourself with the **Object Oriented Programming** (OOP) and create your first classes, objects, and methods!




<img src="https://media.giphy.com/media/YYW0hHizzIOrlhimPG/giphy.gif" width="400">





## Instructions:
> Before we start, make sure to create a new Repl.it and call it "OOP1"!

### Part 1: 
In `main.py` file:
1. Add the following Animal class to your code:
```python
class Animal():
	def __init__(self, name,age,sound,color):
		self.name = name
		self.age = age 
		self.sound = sound	
		self.color = color

	def description(self):
		print(self.name + ": " + self.sound + ", I am " + str(self.age)   + " years old, and my favorite color is " + self.color)
	def eat(self,food):
		print("Yummy! " + self.name + " is eating " + food)
```

2. Using this class, create an **Animal object**.
3. Use the method `description` to introduce your animal.
4. Use the method `eat` and make your animal eat its favorite food.
5. Using the `Animal` class, create a new **method** for this class called `make_sound`, the method should print your animal’s signature sound 3 times. 
6. Make the method print the sound X amount of times (Every time you call the method you should be able to control the amount)


**Good Job! Remember to show your wonderful work to your Instructors and TAs.**

### Part 2: 
1. Create a Runner class (With `name`, `gender`, & `speed`)
2. Create a method called `GetSpeed` that returns the runner's `speed`.
3. Create another method called `Race` - that takes `self` and **another Runner object** that checks who would win if both runners were in a race. 
	- Make sure to check all cases.
	- Make the method announce who is the winner by printing a sentence accordingly.
4. Create at least two more objects and try the methods you created to make sure everything works with no errors.

**Good Job! Remember to show your amazing work to your Instructors and TAs.**


#### Finished early and down for an extra challenge?
### [Click here for Bonus Section!](/Session%209,%20OOP%201/Bonus.md)



<img src="https://miro.medium.com/max/2600/1*TIyf0_kfMRRiJQFAUgp0QQ.png" width="350">
