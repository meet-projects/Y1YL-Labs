# Javascript II - Lab #2 (DOM)

- Using the new knowledge you have just learned about **Javascript** and the **DOM**, you will have to think about a main **Input/Output feature** in your website.
* Below you can find a DOM lab, in case you feel like you need to practice it.


# Javascript II - DOM Lab (Not required)

## Objective: 
During this lab, you will be creating a page about yourself using Document Object Model! You will be using **only Javascript** for this lab.

Some useful links to learn more about DOM:
- W3 Schools: https://www.w3schools.com/js/js_htmldom.asp 
- Presentation: https://tinyurl.com/wgwaupt 






<img src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif" width="400">





## Instructions:
- Copy and paste the code at the end into a new HTML file. Write code ONLY in the update() function. **Do NOT edit any of the HTML.**
- The update() function will be called when the button is clicked.
- Inside the function:
	1. Update the text in “name” element to your name.
	2. Update the text in “age” element to your age.
	3. Update the text in “favorite_food” element to your food.
	4. Update the “favorite_site” element to be your favorite website. Make sure to edit both the attribute AND the text. (Make sure to include the https:// in the link)
	5. Make a new `<p>` element with id “favorite_word”. Make the text in the element your favorite word. Add the element to the body of the HTML.
	6. Make a new `<p>` element with id “favorite_drink” to replace element with id “favorite_food”.
	7. Change the text color of all `<p>` tags into your favorite color.


#### HTML Code to be copied:

```HTML
<!DOCTYPE html>
<html>
<head>
	<title>DOM Lab</title>

	<script type="text/javascript">
		function update() {
			// YOUR JS CODE HERE

		}

	</script>
	
</head>
<!---------- DO NOT EDIT THE HTML BELOW --------->
<body>

	<h2 id="name">My name</h2>
	<p id="age">My age</p>
	<p id="favorite_food">My favorite food</p>
	<a id="favorite_site" href="https://www.google.com">google.com</a>

	<br>
	<button onclick="update()">Update my information</button>
</body>
</html>
```



## Bonus:
- Create a button to change the “name”, “age”, “food”, “favorite_site”, “favorite_word”, and your newly added element to switch between your information and two other MEET students’ information.




##### Great job!
##### Call an Instructor/TA to check your completed tasks
 
 




<img src="https://media.giphy.com/media/l0HlTy9x8FZo0XO1i/giphy.gif" width="350">
