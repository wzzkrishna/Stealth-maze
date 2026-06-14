# Stealth-maze

This is a 2D top-down stealth puzzle game made completely from scratch using basic web coding. The goal of the game is to find your way through a maze, avoid an enemy ghost, and reach the exit safely.

---

## Game Features

* **Random Maps:** The game generates a completely new maze automatically every time you play or clear a level. As you move to higher levels, the maps become much more complex with fewer open paths and more dead ends.
* **Natural Enemy AI:** The red enemy ghost moves around the maze naturally without cheating or walking through walls. It wanders around on its own, but the moment you enter its straight line of sight, it changes to chase mode and runs after you at a fast speed.
* **EMP Shockwave Attack:** If the ghost gets too close to you, you can press the spacebar (or tap the red EMP button on mobile screens) to launch a shockwave. This attack pushes the ghost back and freezes it in place for 3 seconds so you can escape.
* **Smooth Wall Sliding:** The movement engine is designed so your character slides smoothly along the walls when moving diagonally, instead of getting stuck or glitching at the corners.
* **Background Music:** The game supports a looping background music track that starts playing automatically as soon as you make your first movement or click on the screen.

---

## Game Controls

* **Desktop:** Use `W, A, S, D` or the `Arrow Keys` to move your character. Press `Spacebar` to trigger the EMP attack.
* **Mobile:** Use the on-screen arrow buttons to move. It supports pressing two buttons together for diagonal moving. Tap the red center button for the EMP attack.

---

## Technical Details

The entire game is written in pure frontend web code without using any heavy external game engines or frameworks.

* **HTML5 Canvas:** Used for rendering the maze paths, player boxes, and drawing the visual EMP blast waves on the screen.
* **Pure JavaScript:** Written from scratch to handle player input, wall collision detection, level transitions, and the ghost's pathfinding logic.
* **CSS3:** Used for the dark hacker theme setup, font styles, and responsive mobile control buttons.
