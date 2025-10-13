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
*Make sure you document everything in a **Planning Document**(google doc, miro, canva..)

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
You should have a **structured world** stored in a JSON file, and you can print scene info from it.

---

##  Session 2 


###  Step 1: Create Your Player Dictionary  

```python
player = {
    "location": "forest",
    "inventory": [],
    "name: : ""
}
```

---

###  Step 2: Add a Game Loop  

- make sure you update the location of the player.
- make sure you don't have an **infinte loop**.
- handle wrong input/input thay doesn't exist.


---

### Step 3: Add Inventory Features  
Let the player collect or drop items:

```python
command = input("What would you like to do? ").lower()

if command == "take":
    item = input("What do you want to take? ")
    if item in world[loc]["items"]:
        player["inventory"].append(item)
        world[loc]["items"].remove(item)
        print(f"{item} added to your inventory.")
```

Use loops to display the player’s inventory:
```python
for i, item in enumerate(player["inventory"], start=1):
    print(f"{i}. {item}")
```

 **By the end of Session 2:**  
You should have a **playable prototype** — players can move, interact with scenes, and pick up or drop items.

---

##  Sessions 3–4 

Now it’s time to build, refine, and get creative!
**make sure you include a menu of all the functionalities you have in your project for a better user excperince**

###  Minimum  Requirements 
- A functional **game loop** with movement between scenes  
- Use of **`.json`** file for your world data  
- Use of **lists** for player inventory or tracking  
- At least **two possible endings** based on player choices or items
  

---

### 🌟 Bonus Ideas
- Random events with `import random`  
- Health or points system  
- Track visited locations  
- Save/load player progress using JSON  
- Add ASCII art or colored text  

---

##  Final Deliverables
Each pair submits:
- `main.py` → your main game code  
- `world.json` → your story world  
- `planningDoc.word` → short reflection:
  - How you divided the work
  - The Story line
  - What was hardest  
  - One thing you’re proud of  

---

###  Example Reflection
> “I designed the world while my partner handled the loop logic.  
> We struggled a bit with nested dictionaries but figured out how to use `.get()` for cleaner lookups.  
> I’m proud that our story actually has three endings and random dragon attacks!”

---

**Be creative.  
Surprise your users.  
And remember: **good code tells a story — great code *is* a story.****
