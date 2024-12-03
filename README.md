Poker Game Application
Overview
This repository contains a Poker Game Application developed in Java. The project is designed to simulate the mechanics of a poker game, including managing player interactions, handling game states, placing bets, exchanging cards, and determining winners. It features a user-friendly graphical interface and implements several key design patterns like Strategy and Template Method to ensure a clean and extensible codebase.

Features
Poker Gameplay Simulation:

Players can join tables, place bets, pass, and exchange cards.
Hands are evaluated to determine the winner of each round.
Automated handling of game flow, including betting rounds and card exchanges.
Interactive User Interface:

Players can visually interact with their cards and the game through an intuitive GUI.
Real-time updates on the game state, player actions, and winnings.
Design Patterns:

Strategy Pattern: Used to manage dynamic behaviors for different player actions and states during the game.
Template Method Pattern: Ensures a consistent flow for game mechanics like placing bets or exchanging cards.
Backend Architecture:

Centralized game logic handled by the Fachada service.
State management for both game rounds (Mano) and player actions.
Extensibility:

The codebase is structured to allow easy addition of new poker rules, player strategies, or interface improvements.
Technologies
Programming Language: Java
UI Framework: Java Swing
Design Patterns: Strategy, Template Method, Observer
