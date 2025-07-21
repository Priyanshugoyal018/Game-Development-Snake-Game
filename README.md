# Game-Development-Snake-Game
Company : CODETECH IT SOLUTION 
Name : Priyanshu Goyal
Intern id : CT08DG1149 
Domain : C++ Developer
Duration : 8 Weeks

This is a classic console-based Snake game that I made in C++.
It looks simple, but building it taught me a lot about how games actually work behind the scenes.
## How I made it:
The whole game runs in a loop with four main parts: Setup(), Draw(), Input(), and Logic().

Setup() initializes everything: the starting position of the snake, the score, the first fruit’s location, etc.

Draw() handles displaying the game on the console. It prints the borders, the snake’s head (as O), its tail (as o), and the fruit (as F). It updates the screen every frame so it feels like things are moving.

Input() checks if the player presses any keys (W, A, S, D to move; X to exit) and updates the direction accordingly.

Logic() is where the real game rules are applied: moving the snake forward, adding to the tail when it eats the fruit, checking for collisions with itself, and wrapping the snake around if it crosses the edge.

## Features:
The game starts by default moving to the right, so it doesn’t feel stuck at the beginning.

You can’t instantly turn back in the opposite direction (e.g., from left to right) to avoid crashing into yourself by mistake.

Fruits never spawn on the snake’s body – there’s a check to make sure of that.

The game keeps getting harder as your tail grows longer, and your score increases by 10 every time you eat a fruit.

## What I learned:
Making this game helped me understand:

How to manage game loops

Handling real-time user input in C++

Basic logic for collision detection

How to draw a “game” inside the console window

Even though it looks simple, it’s a good example of how logic, conditions, and loops come together to create something fun and interactive.

## OUTPUT
https://github.com/user-attachments/assets/640e73e1-0c09-4c72-8f35-b946ff1fe0a8
