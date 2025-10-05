# @lliance

**@lliance** is a two-player 2D platformer game, where Red and Blue collaborate across five floors on one screen to reach the exit.
 
## Gameplay

- Players progress through **five levels** in the game.  
- Players automatically fall when there is no floor beneath them.  
- The objective is to reach the **goal tile** at the bottom level.  
- Players cannot move through walls that surround the map.  

The map is read from a file and displayed in the game. Each tile in the map is represented by a **unique enum value** corresponding to different states of the game.  

### Players

- **Player Red**: represented as a red `@`, moves with **WASD** keys.  
- **Player Blue**: represented as a blue `@`, moves with **arrow keys**.  

**Movement keys:**  
- W / ↑ : Jump  
- A / ← : Move left  
- D / → : Move right  

### Collaboration

Players can interact with **buttons** that change parts of the map to help them progress.  
- Buttons can open floors to go down or unlock doors to move forward.  
- Players must **collaborate** to figure out how to use the buttons.  

### Hazards

- If a player touches tiles of the wrong color or collides with moving objects, they lose.  
- Press **Space** to restart the game.  

## How to Play

To play **@lliance**, run the following commands in your terminal:

```bash
make
./alliance game.map
