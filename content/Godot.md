---
tags:
  - Programming
  - GameDev
draft: false
---

Nodes are fundamental building blocks of Godot Engine

Scenes are bundle of nodes, making us able to build one at a time. You could also nest scenes together.

Example scene tree:
- Game (Root)
	- Player
		- Graphics
		- Collider
	- Enemy

Player are create using CharacterBody which is a physics body

Press F to center

Delta: amount of time gone since last frame, compensate for variation in framerate

$movement*delta$ make movement independent of framerate

_process() run at a variable framerate
_physics_process() run at a constant framerate

---
# References
1. [How to make a Video Game - Godot Beginner Tutorial - YouTube](https://www.youtube.com/watch?v=LOhfqjmasi0)