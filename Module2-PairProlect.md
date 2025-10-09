# 🧠 Pair Project 2025/26  
## *World Builder: The Interactive Story Engine*  

<img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="300px">

### **Objective:**  
In this project, you and your partner will design and code your own *interactive story engine* — a text-based world that reacts to the player’s choices.  
You’ll use **dictionaries**, **lists**, and **loops** to model a world, track a player’s state, and let users explore and make decisions that shape the outcome.  

This project builds directly on your chatbot experience — but this time, you’re creating a *mini game engine* where **data and logic** work together.  

---

## 🧩 Session 1 – Dictionaries & Data Structures  

### 🧠 Focus:  
Designing and building your **world structure** using nested dictionaries (or a JSON file).  

### 💬 Concepts:
- Key-value pairs  
- Nested dictionaries  
- `.keys()`, `.values()`, `.items()`  
- Separating **data** from **logic** using JSON  

---

### 🗺️ Step 1: Design Your World  
Before you start coding:  
- Brainstorm your story idea (fantasy, sci-fi, mystery, etc.)  
- Plan **4–5 locations** or “scenes”  
- Decide what information each location will include:
  - A short **description**  
  - **Options** for where the player can go next  
  - **Items** the player can find  

Example sketch:
```
forest → cave → treasure room
   ↓
 village
```

---

### 🧱 Step 2: Build Your World Dictionary  

```python
world = {
    "forest": {
        "description": "🌲 You are in a dark forest. Paths lead to a cave and a village.",
        "options": {"cave": "cave", "village": "village"},
        "items": ["stick"]
    },
    "cave": {
        "description": "🪨 The cave is cold and echoes with strange sounds.",
        "options": {"forest": "forest"},
        "items": ["stone"]
    }
}
```

Or, store your world in a **`world.json`** file:  

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

### ✅ Step 3: Test Your Data
Print out all the locations and descriptions:
```python
for name, info in world.items():
    print(name, "→", info["description"])
```

🧭 **By the end of Session 1:**  
You should have a **structured world** stored in a dictionary or JSON file, and you can print scene info from it.

---

## 🔁 Session 2 – Lists & Iteration Patterns  

### 🧠 Focus:  
Creating your **player system** and interactive **game loop** using lists and iteration.

### 💬 Concepts:
- Lists: `.append()`, `.remove()`, `.sort()`, `.count()`, `.index()`  
- Iterating through lists and dictionaries (`for`, `while`, `enumerate()`)  
- `len()` patterns  
- (Optional) `zip()`  

---

### 🧍 Step 1: Create Your Player Dictionary  

```python
player = {
    "location": "forest",
    "inventory": []
}
```

---

### 🔄 Step 2: Add a Game Loop  

```python
while True:
    loc = player["location"]
    print(world[loc]["description"])
    print("Available paths:", ", ".join(world[loc]["options"].keys()))

    choice = input("Where do you want to go? ").lower()

    if choice in world[loc]["options"]:
        player["location"] = world[loc]["options"][choice]
    elif choice == "quit":
        break
    else:
        print("That path doesn’t exist!")
```

---

### 💼 Step 3: Add Inventory Features  
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

🧭 **By the end of Session 2:**  
You should have a **playable prototype** — players can move, interact with scenes, and pick up or drop items.

---

## ⚒️ Sessions 3–4 – Work Time & Creative Expansion  

Now it’s time to build, refine, and get creative!  

### ✅ Required Features
- A functional **game loop** with movement between scenes  
- Use of **nested dictionaries** for your world data  
- Use of **lists** for player inventory or tracking  
- At least **two possible endings** based on player choices or items  
- Demonstrate at least **four** of these methods:  
  `.get()`, `.append()`, `.remove()`, `.items()`, `.keys()`, `.values()`, `.sort()`, `.reverse()`, `len()`  

---

### 🌟 Bonus Ideas
- Random events with `import random`  
- Health or points system  
- Track visited locations  
- Save/load player progress using JSON  
- Add ASCII art or colored text  
- Funny or surprising endings  

---

## 🏁 Final Deliverables
Each pair submits:
- `main.py` → your main game code  
- `world.json` → your story world  
- `README.md` → short reflection:
  - How you divided the work  
  - What was hardest  
  - One thing you’re proud of  

---

### 🧩 Example Reflection
> “I designed the world while my partner handled the loop logic.  
> We struggled a bit with nested dictionaries but figured out how to use `.get()` for cleaner lookups.  
> I’m proud that our story actually has three endings and random dragon attacks!”

---

### 🎉 Final Note
Be creative.  
Surprise your users.  
And remember: **good code tells a story — great code *is* a story.**
