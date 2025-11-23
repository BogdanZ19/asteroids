# Asteroids

A simple 2D Asteroids-style game implemented in Python.

## 🎮 Overview

This project is a Python recreation of the classic arcade game *Asteroids*. You pilot a spaceship, shoot asteroids, avoid collisions, and survive as long as possible.
The codebase is structured with separate modules for the player, asteroids, shots, and the playing field (asteroid field).

## 📂 Project Structure

Here’s a summary of key files and modules:

* `main.py` – Entry point: initializes game loop and handles overall game flow.
* `player.py` – Defines the player spaceship: movement, rotation, shooting, collision logic.
* `asteroid.py` – Defines individual asteroid objects: size, movement, splitting when shot.
* `asteroidfield.py` – Manages a field of asteroids: creation, update, lifecycle.
* `shot.py` – Represents bullets/shots fired by the player.
* `circleshape.py` – Utility module for circular collision shapes / geometry.
* `constants.py` – Shared constants (speeds, sizes, colours, etc.).
* `logger.py` – Logging and debug output support.
* `pyproject.toml` – Project metadata and dependencies.
* `.gitignore` – Files to ignore in version control.

## 🛠️ Requirements & Setup

* Python (version 3.x recommended)
* Any additional dependencies: install via `pip install -r requirements.txt` 
* To run the game:

  ```bash
  python3 main.py
  ```

  (Run from the project root directory.)

## 🎮 How to Play

* Use keyboard controls (WASD, SPACE) to steer the spaceship, shoot asteroids, and avoid collisions.
* Destroy asteroids: large ones split into smaller ones, as in the classic game.
* Survive as long as possible 

## 🚀 Features & Highlights

* Modular Python code: clear separation of concerns (player, asteroids, shots, field).
* Uses object-oriented programming for game entities.
* Basic collision detection for interacting game objects.



