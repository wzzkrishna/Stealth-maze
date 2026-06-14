# Stealth Maze

This is my personal game development project. It includes two different game experiences made completely from scratch using basic web coding. The main project is a stealth puzzle game called **Stealth Maze PRO**, and the second one is my interactive **RPG Portfolio** layout.

---

## 1. Stealth Maze PRO

This is a 2D top-down game where you play as a character trying to escape a dangerous maze. A red enemy tracks you down, and you have to use strategy to avoid it and reach the exit.

### Main Features
* **Random Maps:** The game generates a new map automatically every time you play or change levels. As the level increases, the maze gets harder with more dead ends.
* **Smart Enemy:** The red enemy does not cheat or walk through walls. It walks around randomly, but the moment you come into its line of sight, it starts chasing you at a fast speed.
* **EMP Attack:** If the enemy gets too close, you can press the spacebar (or tap the EMP button on mobile) to launch a shockwave. This pushes the enemy back and freezes it for 3 seconds so you can run away.
* **Smooth Movement:** The movement controls are fixed so your character slides smoothly along the walls instead of getting stuck or glitching at the corners.
* **Background Music:** The game includes an option to load ambient background music that starts playing automatically on your first click or movement.

### Controls
* **Desktop:** Use `W, A, S, D` or `Arrow Keys` to move. Press `Spacebar` to use the EMP attack.
* **Mobile:** Use the on-screen direction buttons to move and the red center button for the EMP attack. Supports pressing two buttons together for diagonal movement.

---

## 2. My RPG Portfolio Layout

This is a creative setup where you can move a character on a green map and walk up to different buildings representing portfolio sections like **My Education**, **My Projects**, and **Contact Me**. Pressing the action button opens up the details for that specific section.

---

## Technical Details

Everything in this project is built using pure frontend code without downloading any heavy external software or game engines.

* **HTML5 Canvas:** Used for drawing the maze grids, player boxes, and visual attack waves on the screen.
* **Pure JavaScript:** Written from scratch to handle player movement logic, wall collisions, and the enemy tracking system.
* **CSS3:** Used for the dark theme, user interface layout, and responsive mobile buttons.

---

## How to Setup the Code

1. Download the `index.html` file into a folder on your computer.
2. Inside that folder, create a new folder named `sounds`.
3. Put your background music file inside the `sounds` folder and update this line in the code with your file name:
   ```javascript
   const bgMusic = new Audio('sounds/your-music-file.mp3');
   
