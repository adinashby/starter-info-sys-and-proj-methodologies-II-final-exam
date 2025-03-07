# Information System and Project Methodologies II - Final Exam

This template repository is the starter project for Integrative Project in Information System and Project Methodologies II Final Exam. Written in C#.

## Instructions
- This exam is **open book**, and you are allowed to use the internet. However, **you cannot use AI tools or collaborate with others to solve the problems.**
- You must design and implement two **independent game features**, each requiring the integration of **two design patterns**.
- Clearly explain your **choice of design patterns** and how they interact within the game.
- Submit your **source code** along with a **short documentation** describing the design choices and implementation details.

## Question 1: Implement a Game Asset Management System (50%)

### Problem Statement
You are tasked with developing a **Game Asset Management System** that efficiently loads, caches, and provides access to game assets such as textures, models, and sound files. Your implementation should incorporate at least **two design patterns** from the following list:

- **Flyweight**: Optimize memory usage by sharing common assets among different game objects.
- **Facade**: Provide a simplified interface for asset loading and retrieval.
- **Proxy**: Implement lazy loading of assets, loading them only when needed.
- **Bridge**: Separate abstraction (asset types) from implementation (asset storage methods).

### Requirements
- Implement at least **two design patterns** from the above list.
- Write a short report (a page or less) explaining how the design patterns were applied and their benefits.
- Your implementation should be **object-oriented** and well-structured.
- Ensure the code is **modular** and follows **SOLID principles**.

## Question 2: Implement a Character Customization System (50%)

### Problem Statement
You are required to develop a **Character Customization System** that allows players to customize their character’s appearance, attributes, and abilities. The system should support flexible object creation and allow modifications to the character without modifying its core structure. Your implementation should incorporate at least **two design patterns** from the following list:

- **Prototype**: Enable cloning of character templates to quickly create new characters with predefined attributes.
- **Builder**: Provide a structured way to construct a character step by step.
- **Factory Method**: Encapsulate character creation logic for different character classes (e.g., Warrior, Mage, Rogue).
- **Bridge**: Decouple character abstraction (appearance, abilities) from its implementation (different storage formats or rendering engines).

### Requirements
- Implement at least **two design patterns** from the above list.
- Write a short report (a page or less) explaining how the design patterns were applied and their benefits.
- Your implementation should be **object-oriented** and well-structured.
- Ensure the code is **modular** and follows **SOLID principles**.

---

## Evaluation Criteria
- **Correctness (70%)**: The game feature meets the functional requirements and integrates the selected design patterns properly.
- **Code Quality (10%)**: The implementation follows clean code practices, including modularity and proper naming conventions.
- **Documentation (20%)**: A brief report explaining the system architecture, why certain patterns were chosen, and how they improve the system.

This final exam assesses your ability to **apply, combine, and justify** the use of advanced design patterns in game development. **Good luck!**

