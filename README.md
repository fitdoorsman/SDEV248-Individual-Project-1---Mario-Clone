# 🏀 Late For Tip-Off

> A frantic 2D platformer built using the **Godot Engine** where you race across campus to secure your starting spot!

## 📝 Overview

You play as **Titus "The Titan" Guard**, the starting point guard for the Ivy Tech Titans. Tip-off is in just minutes, and you are racing across campus to reach the gym before the clock runs out! Along the way, you must avoid enemies, collect crucial energy drinks, and manage your limited lives while navigating environmental hazards.

### 🏃 Mission: Court Crash

To secure your starting spot, you must meet two main goals:

1.  Collect a minimum of **10 Titan Energy Drinks** for pre-game fuel.
2.  Reach the **Gymnasium Main Doors** before the tip-off buzzer sounds.

---

## 🎮 Gameplay & Controls

Move through the level while avoiding enemies and obstacles.

| Action | Input | Description |
| :--- | :--- | :--- |
| Move Left | $\leftarrow$ Arrow | Move character left |
| Move Right | $\rightarrow$ Arrow | Move character right |
| Jump | **Spacebar** | Perform a jump |
| Restart | Restart Button | Appears after failure/game over |

---

## ❤️ Lives System

* The player begins with **3 lives**.
* Touching an enemy or falling off the level removes **1 life**.
* When lives reach **0**, the **Game Over** screen appears, offering a restart option.

## ✅ Win & Failure Conditions

| Condition | Requirements | Outcome Message |
| :--- | :--- | :--- |
| **🏆 Win** | Collect **10 or more** drinks AND Enter the gym door. | *Secured your spot!* |
| **❌ Failure** | Reach the gym with **fewer than 10 drinks**. | "Not enough drinks! Another player started." |
| **💀 Game Over** | Losing **all lives** (reaches 0). | *(Triggers Game Over screen with Restart Button)* |

---

## ⚙️ How to Run

This project requires the **Godot Engine 4** to run.

1.  Download or clone this repository.
2.  Extract the project ZIP file included in the repository.
3.  Open **Godot Engine**.
4.  Click **Import** and select the extracted project folder.
5.  Run the main scene, `Main.tscn`, to begin playing!

## 📄 License

This project is for educational use. Feel free to modify, build on, and share this project!
