## Overview:
TunnelMan is a grid‑based digging and exploration game where the player controls a miner navigating an underground oil field. The objective is to collect all barrels of oil while avoiding or dealing with Protesters, falling boulders, and other hazards.

This project is a full C++ implementation of the TunnelMan game as described in the course specification. It includes all required actors, world logic, movement rules, interactions, and tick‑based game behavior.

## Features:
-Fully functional StudentWorld engine

-Complete implementation of all Actors, including:

-TunnelMan

-Regular Protesters

-Hardcore Protesters

-Earth

-Boulders

-Squirts

-Gold Nuggets

-Barrels of Oil

-Sonar Kits

-Water Pools

-Accurate tick‑based game loop

-Correct movement, digging, collision, and visibility logic

-Protester AI including:

-Line‑of‑sight detection

-Random movement

-Shouting

-Bribing

-Hardcore BFS pathfinding

-Boulder falling physics

-Item pickup, expiration, and scoring

-Level progression and life system

## Game Mechanics:
-64×64 world grid

-4×4 actor sprites

-Earth occupies rows 0–59

-Central starting shaft

-Randomized placement of boulders, oil, and gold

-Increasing difficulty per level

## Project Summary:
-This project implements a complete tick‑driven 2D game engine modeled on the TunnelMan specification. The system is built around a central StudentWorld controller that manages world initialization, per‑tick updates, actor lifecycles, collision handling, and level progression. All game entities derive from a shared Actor base class, with specialized subclasses implementing movement rules, interaction logic, and state machines.

-Key systems include:

-Actor Framework: Unified interface for per‑tick behavior, life state, and spatial logic.

-StudentWorld Engine: Coordinates actor updates, spawning, removal, Earth grid management, and HUD updates.

-TunnelMan Logic: User‑driven movement, digging, squirt creation, sonar usage, and inventory handling.

Protester AI: Random movement, line‑of‑sight detection, shouting, bribing rules, stun timers, and Hardcore BFS pathfinding.

Boulder Physics: Stable → waiting → falling state transitions with collision and bonk interactions.

Goodie System: Pickup rules, temporary visibility, expiration timers, and scoring effects.
