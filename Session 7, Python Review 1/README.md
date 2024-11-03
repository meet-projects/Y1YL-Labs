# Y1 Yearlong 2023/24 - Python Review Lab
## Building a Basic AI Chatbot in Python

**Objective:** Your task is to program a simple AI chatbot in Python using basic fundamentals such as dictionaries, loops, and conditional statements.

<img src="https://media.giphy.com/media/S60CrN9iMxFlyp7uM8/giphy.gif" width="300px">

**Minimum Requirements:**
- Use of dictionaries which will tell the bot what to respond to the user input.
- Use a loop to keep the chatbot running until the user decides to exit.
- Handle cases where the user enters unrecognized input.

**Instructions:**

1. **Understanding the Basics // Predefined Responses**
   - Basic AI chatbots work as a dictionary, where you build a dictionary of user input as keys and map them to AI responses as values. It may look something like this:
     ```python
     responses = {
         "hello": "Hello! How can I assist you?",
         "how are you": "I'm just a computer program, but I'm here to help!",
         "goodbye": "Goodbye! Have a great day!",
         # Add more responses here
     }
     ```

2. **Writing the Main Chat Loop**
   - Use a `while` loop to keep the chatbot running until the user decides to exit.
     - If the user enters "exit" the program should stop.
   - The chatbot looks up the user's input in the `responses` dictionary and provides a response if it finds a match.
     - Hint: use `input()` function to recieve user input.
     - Convert the user's input to lowercase to make responses case-insensitive.
     - 
******Submit your work before adding any external libraries******

3. **Choose your own Library**
   - We talked about Libraries in the summer(Examples for libraries:Turtle,Random)
   - This is your chance to get creative, choose at least one library from this document(https://docs.google.com/document/d/1fzhI12m9k3GM7Ouq23P5Tb_vQCR2a1wq19tKfOe9dqo/edit?tab=t.0#heading=h.stt3o5wpb2vc) and incorporate it in your code!
   - (you can research and choose other libraries but get it approved by your instructors first!) 

4. **Extending the Chatbot (Optional / Bonus)**
   - Add more responses to improve the chatbot's conversational abilities.
   - Consider adding conversation history.
   - If the chatbot does not know how to handle an input, it should ask the user for clarification or suggest adding a response.
   - Ensure that the chatbot understands user input even if it is not written exactly as in the `responses` dictionary.

**Good luck with your chatbot programming! Feel free to seek help from online resources or refer to external tools, but be prepared to explain your code line by line.**










