# FSD-project7
)

🕹️ Code Breaker – The Array Heist
🔐 Game Concept

You are a hacker in training, trying to break into a secure digital vault by manipulating an array of numbers.
The password is hidden as a secret numeric pattern inside the array.
Your goal is to insert, delete, and search elements in the array to uncover the hidden code before time runs out!

🚀 Features
🎯 Core Mechanics
Operation	Description
Insert at Index	Add a number at a chosen index (shifts elements to the right).
Delete at Index	Remove a number from a chosen index (shifts elements left).
Search Pattern	Perform a linear subarray search (e.g., find [2,1,4]).
Reset	Clears the entire array to start over.
🧠 Educational Concepts

Array insertion and shifting

Array deletion and compaction

Linear search and subarray matching

Array index bounds validation

🪄 Gameplay Overview
1. Visual Array Display

8–10 cells in a horizontal row.

Each cell holds a number (0–9) or is empty.

Example: [ 3 ][ 1 ][ 7 ][ ][ 2 ][ 1 ][ 4 ][ 9 ].

2. Operations Panel

Inputs and buttons provided for:

Index (0–9)

Value (0–9)

Pattern (e.g., 2,1,4)

Buttons:

Insert

Delete

Search

Reset

3. Animations
Action	Animation
Insert	Cells slide right, new value fades in
Delete	Cell shrinks and fades, others slide left
Search	Highlights scanning window step-by-step
4. Feedback System

Dynamic messages appear, such as:

“Inserted 5 at index 3!”

“Deleted element at index 2.”

“Pattern [2,1,4] found at index 4!”

“Index out of bounds!”

🧩 Extra Game Modes
💣 Auto-Generated Secret Pattern

On load, a random pattern (e.g., [3,7,1]) is generated.

Your task: Insert and search digits until you find it.

Displays “Level Complete!” when found.

⏱️ Time Attack Mode

60-second countdown.

Timer shown in status bar.

Ends with: “You cracked the code in 23 seconds!”.

🔊 Sound Effects
Sound	Event
Beep	Successful insert/search
Buzz	Error or invalid input
Fanfare	Code successfully cracked!
🧱 Levels
Level	Description
1	Find any 2-digit pattern
2	Find a 3-digit pattern
3	Find the pattern in reverse order
🖥️ How to Run

Download or copy the project files.

Make sure you have this file:

index.html
README.md


Open index.html in your browser:

Right-click → “Open with” → Choose Chrome/Edge/Firefox

OR drag the file into a browser window.

Start playing!

⚙️ Technologies Used

HTML5 – structure & layout

CSS3 – styling and animations

JavaScript (ES6) – logic and interactivity

Web Audio API – sound effects

🧑‍💻 Developer Notes

The game is fully client-side (no server or installation needed).

All operations are animated and educational — great for learning array logic.

Easily customizable for classroom demonstrations or projects.

🏆 Example Objectives

Practice insertion and deletion logic.

Implement your own search algorithm improvement.

Extend with score system, multiple levels, or hint mode.
