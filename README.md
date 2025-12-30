# C++: Card Game Logic Systems
**University Year 1 | Game Software Engineering**

A technical exploration of Object-Oriented Programming (OOP) in C++, focusing on class architecture, data encapsulation, and the evolution of complex game logic.

> **[🔗 View the full technical breakdown on my Portfolio](https://sites.google.com/view/myles-coleman/projects/game-software-engineering)**

## 🕹️ Project Overview
This repository demonstrates the progression of a card-based logic engine. It begins with a foundational hand-comparison system and scales into a feature-complete implementation of Pontoon, featuring automated dealer AI and advanced state management.

## 📂 Repository Contents

### 1. 01-Standard-Comparison
A foundational prototype focused on core OOP class structure.
* **Logic:** Deals five cards to multiple players (2–5) and determines a winner based on the highest aggregate hand value.
* **Engineering Focus:** Implementation of modular classes for `Deck`, `Hand`, and `PlayingCard` to ensure clean data handling.

### 2. 02-Pontoon
A significant evolution of the base system, implementing the full ruleset of Pontoon (Blackjack).
* **Dealer AI Behaviour:** Developed an automated dealer that executes logic-based decisions, twisting on hand values of 16 or lower.
* **Win-State Logic:** Engineered complex validation for specific win conditions, including "Bust" states, "Pontoon" (21), and the "Five Card Trick".
* **Dynamic Value Calculation:** Implemented a `HandValue` system capable of handling the dual-value nature of Aces to determine the optimal score for the player.

## 🛠️ Technical Skills Demonstrated
* **Object-Oriented Programming:** Inheritance, encapsulation, and class modularity.
* **Logic Engineering:** Automated AI decision-making and input validation.
* **Data Management:** Utilising vectors and custom structs to manage real-time game states.

## 💻 Technical Specs
* **Language:** C++
* **Compiler:** Visual Studio
