# Y1 Yearlong 2025/26 - individual Project
## Building a Basic AI Chatbot in Python

**Objective:** Your task is to program a simple AI chatbot in Python using fundamentals such as dictionaries, loops, and conditional statements and functions.
*Important Note: this is a much simpler chatbot than the ones you might be using(Gemini,ChatGPT..), those chatbots do not operate on a dictionary and they use more advanced logic than the one we will rely on.

<img src="https://media.giphy.com/media/S60CrN9iMxFlyp7uM8/giphy.gif" width="300px">

**Minimum Requirements:**
- Use of dictionaries which will tell the bot what to respond to the user input.
- Use a loop to keep the chatbot running until the user decides to exit.
- Handle cases where the user enters unrecognized input.

**Instructions:**
# Session 1

1. **Understanding the Basics // Predefined Responses**
   - A dictionary will act as our "database" meaning we will store and retrive information/data from it, we will start with it being static and as we progress we will make it more and more dynamic.
   - Basic AI chatbots work as a dictionary, where you build a dictionary of user input as keys and map them to AI responses as values. It may look something like this:
     ``python
     responses = {
         "hello": "Hello! How can I assist you?",
         "how are you": "I'm just a computer program, but I'm here to help!",
         "goodbye": "Goodbye! Have a great day!",
         # Add more responses here
     }
     ``
     
  2. let's make the chatbot dynamic!
    - take the user's name and age(don't lose them we will use them later!)
    - Calculate and show the user what's their age in months, weeks, days, minutes or seconds.(feel free to do all of them!)
    - make the chatbot dynamic: whenever you run your code and have to enter a question, it should show the user's name, when you run your code it should look something like this:
        ```terminal
           Sam:hello
           ChatBot:Hello! How can I assist you?
         ```
  -  Test you code out, does each key co-respond to it's value
  -  *note: this is just one way to make the chatbot dynamic, think of other ways, other information that you can take from the user and use.
  -  Add more responses to your dictionary to cover more questions.

**Bonus:**
- Use AI to generate 3 fun greetings and select one randomly (Uses list + random())

  
# Session 2


1. **Writing the Main Chat Loop**
   - Use a `while` loop to keep the chatbot running until the user decides to exit.
     - If the user enters "exit" the program should stop.
     - Include more than one "phrase" to exit the program; "bye","exit","stop"...
   - The chatbot looks up the user's input in the `responses` dictionary and provides a response if it finds a match.
     - Hint: use `input()` function to receive user input.
     - Make responses case-insensitive, meaning that the program considers "HELLO" and "hello" and "HellO" as the same input.
     - Add menu of options (e.g., "Ask me a question", "Tell me a joke", etc.) to make your chatbot more user friendly.
   

2. **Bonus**
   - Add key recognition - Hint: look up `in`, `.lower()`.


# Session 3

1. Expand the chatbot to:
    - Respond to yes/no questions (e.g., “Are you hungry?”)
    - Handle edge cases with try/except
    - Give different responses based on user input
2. **Bonus**
   - Add "personality" to your chatbot.
  

# After you're done with everything from the previous sessions you can move on to this sesction:    
1. **Choose your own Library**
   - We talked about Libraries in the summer(Examples for libraries:Turtle,Random)
   - This is your chance to get creative, choose at least one feature from the document below, and research the most appropriate library to implement the feature
     (https://docs.google.com/document/d/1UcPuJOgiokcIU_ED68-UK9Qwu7wZdXfEe14PPovoev4/edit?usp=sharing) and incorporate it in your code!
   - (you can research and choose other features but get it approved by your instructors first!) 

2. **Extending the Chatbot (Bonus)**
   - Add more responses to improve the chatbot's conversational abilities.
   - Consider adding conversation history.
   - If the chatbot does not know how to handle an input, it should ask the user for clarification or suggest adding a response.
   - Ensure that the chatbot understands user input even if it is not written exactly as in the `responses` dictionary.

**Good luck with your chatbot programming! Feel free to seek help from online resources or refer to external tools, but be prepared to explain your code line by line.**











