# Bootstrap - Lab

## Objective: 
In this lab, you will experiment with Bootstrap's grid system and its' many different elements, get to know how to work with it, and create ***responsive*** web applications suitable to **any device**!





<img src="https://cdn.worldvectorlogo.com/logos/bootstrap-5-1.svg" width="150">





## Instructions:
### Part 1:
1. Create a new file and call it "exercise.html".
2. Create a table layout using a bootstrap grid **(Without HTML tables)** that includes 3 types of your favorite creatures.  
    - The table layout should look similar to this (image below) for all types of screens.  
    - The **name** needs to be a _link_ to a wiki page about that creature.

<img src="https://github.com/meet-projects/Y1YL-Labs/blob/master/Session%206%2C%20Bootstrap/BootstrapGrid.png" width="300">

#### Bonus:  
Open the website you made then right click and inspect element. As you notice, the image isn't compatible with the screen size and can sometimes get out of the borders of the column that includes it. Google how to fix that. (hint: you need to make the image's width compatible with its parent).

  <br>

### Part 2:  
1. Make a carousel that displays the images of the animals you listed previously.
2. Add a "Primary" Button with the text "Next", and a "Secondary" Button with the text "Previous".

#### Bonus:
Style and design all buttons and links buttons.


<img src="https://webdevpuneet.com/wp-content/uploads/2019/09/Screenshot_84.png" width="500">  
  
##### Great job!
##### Call an Instructor/TA to check your completed tasks
 
 


## Bonus Part:  

Copy this code written in the bottom and paste it in a file called calculator.html for this portion of the lab.  
Open the calculator.html file in your browser (Chrome/ Firefox). What do you see?
You are right! It's the ugliest thing you've seen all day.  
Your job is to make it look more like a calculator using your knowledge about the Grid layout(rows, columns) and Bootstrap components (Buttons, inputs)  
Make an interface for a calculator (out of inspiration? click here or here)  

The must-haves for the calculator are:
- Buttons from 0-9
- Buttons for addition, subtraction, division, and multiplication
- A Textbox for showing the result
<img src="https://media.istockphoto.com/vectors/calculator-vector-id531633071?k=20&m=531633071&s=612x612&w=0&h=mEZntyKX_pFEupTpZLV9-asMCkGJk-uA8L0PUEpG-BQ=" width="150">


#### Above & Beyond Bonus:
Using Javascript, make the calculator work!

## Code for  `calculator.html`:
```
<!doctype html>
<html lang="en">
 <head>
   <!-- Required meta tags -->
   <meta charset="utf-8">
   <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

   <!-- Bootstrap CSS -->
   <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
   <link rel="stylesheet" href="css/styles.css">
   <title>Hello, world!</title>
 </head>
 <body>
 <div class="container text-center">
   <div class="row justify-content-center">
     <div class="calcBG row col-md-3 ">
       <small>Bootstrap Calculator</small>


       <!-- Write you calculator code here -->






     </div>
   </div>
 </div>
   <!-- Optional JavaScript -->




 </body>
</html>
```


