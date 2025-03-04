# Starter Game - Object-Oriented Escape Game  

## Description  
**Starter Game** is a text-based adventure game built using **object-oriented programming (OOP) principles** in C#. The player navigates through different rooms, interacting with objects and executing commands to progress through the game.  

## Features  
- **Player-Driven Exploration**: Move through rooms, interact with objects, and progress toward escape.  
- **Command-Based Input System**: Uses a **parser** to interpret text commands.  
- **Event-Driven System**: Implements the **Observer pattern** (`NotificationCenter`) to handle game events like winning.  
- **Game Loop**: Continuously reads and executes player commands until the game ends.  
- **Start & End System**: Begins with a **welcome message** and ends upon victory or game termination.  

## Gameplay Flow  
1. **Starting the Game**  
   - The player starts in the entrance room with **20 health points**.  
   - A **welcome message** introduces the game.  
   - Commands are entered through the console.  

2. **Exploring & Executing Commands**  
   - Players can move between rooms, pick up items, and execute actions.  
   - A `Parser` processes valid commands while providing error messages for invalid inputs.  

3. **Winning the Game**  
   - A specific goal or escape condition must be met.  
   - The game triggers a **"playerWonGame"** event, stopping the game loop.  

4. **Game Over**  
   - The player receives a **goodbye message**, and the game terminates.  

## Technologies Used  
- **C#**  
- **Object-Oriented Programming (OOP)**  
- **Observer Pattern (`NotificationCenter`)**  
