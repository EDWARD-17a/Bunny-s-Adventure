# ADVENTURE OF BUNNY

**Author:** Edward  
**Supervisor:** John Hernandez  
https://studio.code.org/projects/gamelab/9df14b89-36bd-43f8-9f81-eb6c599a108b
## Overview
**Adventure of Bunny** is a Code.org Game Lab platformer where you control a bunny through a series of increasingly difficult levels. The goal is to survive hazards, avoid enemies, use seed projectiles to defeat certain threats, and reach the door to advance to the next stage.

The game features:
- Multiple stages with different challenges
- Health points system
- Platform jumping
- Enemy obstacles like bats, rats, and a monster
- Projectile attacks using seeds
- Score tracking
- A final win screen

---

## Gameplay
You play as a bunny with **5 HP**. Each level introduces new obstacles and mechanics:

- **Stage 1:** Avoid spikes and reach the door
- <img width="496" height="496" alt="SCREENSHOT1" src="https://github.com/user-attachments/assets/a966d74b-ac1c-44cf-95dd-1d3e4dc3d76e" />
- **Stage 2:** Avoid a moving bat and reach the door
- 
- **Stage 3:** Jump across platforms while avoiding bats
- 
- **Stage 4:** Use seeds to defeat rats and continue through platform obstacles
- 
- **Stage 5:** Fight a monster by hitting it with seeds to unlock the door
- 
- **Stage 6:** Victory screen with a congratulations message and reward

If your HP reaches **0**, the game ends.

<img width="497" height="496" alt="SCREENSHOT6" src="https://github.com/user-attachments/assets/e1e39382-3b6a-41dd-86bc-5ef0439a2eb0" />
---

## Controls
- **Left Arrow:** Move left
- **Right Arrow:** Move right
- **Up Arrow:** Jump
- **Spacebar:** Fire seed projectile

---

## Game Features

### Player
- Bunny character with animated sprite
- Starts with **5 health points**
- Respawns after taking damage if HP remains
- Can fire seeds as ranged attacks

### Enemies and Hazards
- **Spikes** in Stage 1
- **Bat** in Stage 2
- **Bat group** in Stage 3
- **Rats** in Stage 4
- **Monster** in Stage 5

### Level Progression
The player advances by touching the **door** at the end of each stage. Some levels require defeating enemies before the door becomes available.

### Score System
- Gain **1000 points** for completing each stage
- On the final stage, bonus score depends on remaining HP:
  - `1000 × HP`

---

## Stage Breakdown

### Stage 1
- Background: sky blue
- Hazard: spikes on the ground
- Goal: avoid spikes and enter the door

### Stage 2
- Background: blue
- Hazard: one moving bat
- Goal: avoid the bat and reach the door

### Stage 3
- Background: blue
- Hazards: multiple bats
- Mechanics: moving platforms and jumping challenge
- Goal: navigate platforms and avoid enemies

### Stage 4
- Background: orange
- Hazards: rats moving on platforms
- Mechanics: player can shoot seeds to remove rats
- Goal: survive the platform section and reach the door

### Stage 5
- Background: gold
- Boss battle: monster with **20 HP**
- Mechanic: hit the monster with seeds until defeated
- Goal: defeat the monster to unlock the door

### Stage 6
- Victory stage
- Displays **"Congratulations!"**
- Shows a reward sprite

---

## Sprites
This project uses sprite animations for:
- Bunny
- Door
- Bat
- Rat
- Monster
- Seed projectile
- Hearts / HP icons
- Platforms
- Spikes
- Reward item

If you have a full sprite sheet or image collection, you can add it below.

### Sprite Preview
Add your sprite image here:

```md
![Sprites](path-to-your-sprite-image.png)
