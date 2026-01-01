<img src='./screenshot.png' />

## Shadow Dog vs Monster

## Description
In **Shadow Dog vs Monster**, you play as a courageous dog on a quest to save its world from an invasion of terrifying monsters. Armed with determination and a rolling attack, the dog must defeat each monster to restore peace.

## Live Demo
https://adorable-crisp-2d144a.netlify.app/

## How to run

- Using VS Code Live Server (recommended):
    - Install the Live Server extension.
    - Open the project in VS Code and right-click `index.html` → "Open with Live Server".

- Using a simple local HTTP server (works outside VS Code):
    - With Python 3:
        ```bash
        python3 -m http.server 8000
        ```
        Then open http://localhost:8000 in your browser.

    - With Node.js `http-server` (if installed):
        ```bash
        npx http-server -p 8000
        ```

- Note: Opening `index.html` directly in the browser without a local server may cause some assets to fail to load due to browser file access restrictions. Using a local server ensures images and modules load correctly.

Files of interest:
- `index.html` — game entry page
- `style.css` — styles
- `src/` — game logic (vanilla JS modules)

Optional: To publish a live demo, enable GitHub Pages for this repository and serve the repository root or the `docs/` folder

## Gameplay
- **Objective**: Defeat all the monsters in each level.
- **Controls**:
    - Use the arrow keys (up, down, left, right) to move the dog.
    - Press the **Enter** key to activate the rolling attack mode.
- **Enemies**:
    - Monsters will appear randomly on the screen.
    - Some monsters move slowly, while others are swift and aggressive.
    - Each monster has a different health level.
- **Health and Rolling Attack**:
    - The dog has a health bar. If it gets hit by a monster, its health decreases.
    - When the dog enters rolling attack mode, it becomes invulnerable and can defeat monsters by rolling into them.
- **Winning**:
    - To win, defeat get a target score by defeating monsters.   

## Tutorial
1. **Movement**:
    - Use the arrow keys to move the dog:
        - **Up Arrow**: Move upward
        - **Left Arrow**: Move left
        - **Right Arrow**: Move right
2. **Attacking**:
    - Approach a monster and press **Enter** to activate rolling attack mode.
    - While rolling, the dog is invulnerable and can defeat monsters on contact.
    - **Down Arrow**: Downward attack that kill all enemy below the player 
3. **Health and Energy**:
    - Monitor your health bar at the top of the screen.
4. **Score**:
    - Earn points for defeating monsters.
    - Collect bonus points by completing levels quickly. 

## Ready to Play?
Get ready to roll, bark, and defeat those monsters! Good luck, brave dog! 🐾