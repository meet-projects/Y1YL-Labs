# Y1 Yearlong 2025/26 - individual Project
## Building a Basic AI Chatbot in Python

**Objective:** Your task is to program a simple AI chatbot in Python using fundamentals such as dictionaries, loops, and conditional statements and functions.
*Important Note: this is a much simpler chatbot than the ones you might be using(Gemini,ChatGPT..), those chatbots do not operate on a dictionary and they use more advanced logic than the one we will rely on.


# Session 2

<img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExeW9obGZmcDJlOXZzeXdrbXZyZ3Y0ZnpzaGV1YWR1em5jaWVlM2d3ayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/l3fQ9icfExRfiePrq/giphy.gif" width="500px">

**Instructions:**
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
