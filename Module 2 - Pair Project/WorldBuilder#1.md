#  Pair Project 2025/26  
## *World Builder: The Interactive Story Engine*  

<img src="https://i.pinimg.com/originals/f5/1b/32/f51b32d7580d266e620e3580c2b274d8.gif" width="300px">

### **Objective:**  
In this project, you and your partner will design and code your own *interactive story engine* — a text-based world that reacts to the player’s choices.  
You’ll use **dictionaries**, **lists**, and **loops** to model a world, track a player’s state, and let users explore and make decisions that shape the outcome.  

This project builds directly on your chatbot experience — but this time, you’re creating a *mini game engine* where **data and logic** work together.  

---

## Session 1  


###  Step 1: Design Your World  
Before you start coding:  
- Take 20 minutes to brainstorm your story idea (fantasy, sci-fi, mystery, etc.)  
- Plan **4–5 locations** or “scenes”.
- Decide what information each location will include:
  - A short **description**  
  - **Options** for where the player can go next  
  - **Items** the player can find
  - feel free to add more information!

*Make sure you document everything in the **Planning Document**(google doc, miro, canva..)

Example sketch:
```
forest → cave → treasure room
   ↓
 village
```

---

###  Step 2: Build Your World 

store your world in a **`world.json`** file:  

```json
{
  "forest": {
    "description": "🌲 You are in a dark forest. Paths lead to a cave and a village.",
    "options": {"cave": "cave", "village": "village"},
    "items": ["stick"]
  }
}
```

Then load it in Python:
```python
import json

with open("world.json", "r") as file:
    world = json.load(file)
```

---

###  Step 3: Test Your Data
Print out all the locations and descriptions:


 **By the end of Session 1:**  
You should have a **structured world** stored in a JSON file, and you can print scene info from it as well as a planning document to document your progress and division.

---
