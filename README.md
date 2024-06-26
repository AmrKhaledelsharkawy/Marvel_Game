# Marvel - Ultimate War

## Overview
Marvel - Ultimate War is a strategic game that leverages object-oriented programming (OOP) concepts to simulate an ultimate battle between Marvel characters. This project involves creating a game engine, implementing game logic, and developing a graphical user interface (GUI) to facilitate interactive gameplay. The project is divided into multiple milestones, each building on the previous to achieve a comprehensive and functional game.

## Motivation
The motivation behind this project is to provide a practical exercise in OOP, allowing developers to implement and understand advanced programming concepts through a fun and engaging medium. By simulating a complex game, developers can learn about inheritance, polymorphism, encapsulation, and exception handling in a real-world scenario.

## Features
### General Features
- **Dynamic Game Engine**: Implements game logic and rules based on Marvel characters.
- **GUI Integration**: Interactive graphical interface for enhanced user experience.
- **Exception Handling**: Comprehensive validation and error handling to ensure smooth gameplay.

### Game Specifics
- **Character Management**: Players can select Marvel characters, each with unique abilities and attributes.
- **Turn-Based Actions**: Players take turns to perform actions like attacking, using abilities, and moving on the board.
- **Resource Management**: Actions are governed by resource availability, such as mana and action points.
- **End Game Conditions**: The game checks for victory conditions after each action to determine the winner.

## Tech/Framework Used
- **Java**: Core language for implementing game logic and GUI.
- **Swing**: For building the graphical user interface.
- **JUnit**: Used for writing and running tests to ensure code reliability.

## Development Tools
- **Eclipse/IntelliJ IDEA**: Recommended Integrated Development Environments (IDEs) for development.
- **JUnit**: For unit testing.
- **Git**: For version control.

## Milestones
### Milestone 1: Basic Setup
- **Project Hierarchy**: Establishes the project structure with packages like `engine`, `exceptions`, `model.abilities`, `model.effects`, `model.world`, `tests`, and `views`.
- **Data Structures**: Initial implementation of core data structures and enums such as `EffectType`, `AreaOfEffect`, and `Direction`.
- **CSV Data Loading**: Capability to load game data from CSV files into the application.

### Milestone 2: Game Engine
- **Game Logic**: Implementation of game rules and mechanics, including champion abilities, movements, and attacks.
- **Exceptions**: Comprehensive handling of game-related exceptions to manage invalid actions.
- **Testing**: Unit tests to ensure the correctness of game logic and data integrity.

### Milestone 3: Graphical User Interface (GUI)
- **Interactive GUI**: Development of a user-friendly interface that reflects game actions and states.
- **Real-Time Updates**: Ensures that any action performed in the GUI is synchronized with the game engine.
- **User Input Validation**: Handles all exceptions and validations for user inputs and actions within the GUI.

## Installation
### Prerequisites
Ensure you have the following installed:
- **Java JDK**: [Download Link](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)
- **Git**: [Download Link](https://git-scm.com/downloads)

### Cloning the Repository
```sh
git clone https://github.com/AmrKhaledelsharkawy/Marvel_Game.git
```

### Running the Application
1. **Compile the Project**: Use your IDE to compile the project.
2. **Run the Game**: Execute the main class to start the game.

## How to Play
### For Players
- **Start the Game**: Enter player names and select your champions.
- **Take Actions**: During your turn, you can move, attack, or use abilities.
- **Win the Game**: The game ends when one player’s champions are all knocked out. The remaining player wins.

### For Developers
- **Extend the Game**: Implement additional features or improve existing ones.
- **Fix Bugs**: Identify and fix any issues to enhance gameplay.
- **Contribute**: Submit pull requests with your improvements or new features.

## Contribution
### Reporting Issues
- **Check Existing Issues**: Before reporting, check if the issue already exists.
- **Create New Issues**: Provide detailed descriptions and steps to reproduce the issue.

### Contributing Code
1. **Fork the Repository**: Create your own copy of the repository.
2. **Create a New Branch**: For your changes.
3. **Commit Changes**: With clear and concise commit messages.
4. **Push to Your Fork**: And submit a pull request.

## License
This project is licensed under the Apache 2.0 License.

By contributing to this project, you agree to abide by its terms.

## Contact
For further information or inquiries, please contact the project maintainer via GitHub.

