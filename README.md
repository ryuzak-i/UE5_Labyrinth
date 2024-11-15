# UE5_Labyrinth

## Description
**Unreal Engine 5.4**

The Player's task is to go through all sections of the labyrinth and pick up a reward. The labyrinth consists of 4 sections. The sections are separated by blue doors. Each section has a yellow key that opens the door. Also, in each section there is a red Guard with artificial intelligence. The Player loses if the Guard touches the Player.

The Guard has 3 states: patrolling, chasing and checking. The initial state of the Guard is patrolling. When the Player comes into the Guard's line of sight, the Guard starts chasing the Player. If the Guard loses sight of the Player, the Guard follows the last seen position of the Player and enters the checking state. If the Guard sees the Player again, he starts chasing. If the Guard does not see the Player for a certain time, then the Guard goes into a patrolling state.

To move in the game, use the `WASD` keys. `Space` for jumping, `Shift` for running. The `Esc` key opens the pause menu, and when pressed again, it closes it. The `E` key is used for picking keys and opening doors with keys.

**You can watch the gameplay on YouTube by following this link: [UE5_Labyrinth - Gameplay](https://www.youtube.com/watch?v=lJkwDgJ0l68).**

## Attribution
**Icons by Icons8 (https://icons8.com/):**
- KeyE (https://icons8.com/icon/52183/explicit)
- Blocked (https://icons8.com/icon/12405/unavailable)
- Timer (https://icons8.com/icon/15929/hourglass)
- Keys (https://icons8.com/icon/10497/password-key)

**Audios from Freesound (https://freesound.org/):**
- Background music

> 2024-02-16_Background-Sound_Game-music_Remix by kevp888 -- https://freesound.org/s/723909/ -- License: Attribution NonCommercial 4.0
Game music 2 by CollectionOfMemories -- https://freesound.org/s/723129/ -- License: Attribution 4.0
Background Sound N24 by Valo -- https://freesound.org/s/723121/ -- License: Attribution NonCommercial 4.0

- Win/Lose

> You Win/Lose! Fight Announcer VO (Multiple Takes/Wet) by EvanBoyerman -- https://freesound.org/s/418326/ -- License: Attribution 3.0

- Pick key

> inspect item.wav by niamhd00145229 -- https://freesound.org/s/422709/ -- License: Creative Commons 0

- Open door

> concrete blocks moving3.wav by FreqMan -- https://freesound.org/s/25847/ -- License: Attribution 4.0

- Menu buttons

> Action Heavy.wav by ryusa -- https://freesound.org/s/467555/ -- License: Attribution 4.0

- Footsteps

> Hiking Boot Footsteps on Stone by Fission9 -- https://freesound.org/s/521590/ -- License: Creative Commons 0

- Enemy

> putrid_heartbeat.wav by Asteroiderer -- https://freesound.org/s/439410/ -- License: Creative Commons 0

## Idea of creating
Once, I was sent a technical task for the position of Junior Unity Developer. I didn't have time to implement this project then. But later I decided to try to implement this project not on Unity, but on Unreal Engine. I downloaded the latest version of UE, and started learning from video courses on YouTube. About a month later, I decided that I had acquired enough knowledge to implement this project. But not everything was going as well as I would like. There were some delays due to understanding how artificial intelligence works and reworking the basic logic of the project. Still, I managed to finish this project and bring it to a playable state that I'm not ashamed of. I tried to compress the physical size of the project as much as possible to make it convenient to work with it through GitHub. Below are the requirements for the technical task.

### Tech Task - Junior Unity Developer
Create a simple 3D game where the player controls a character that explores a labyrinth. The goal of the game is to find a way out of the labyrinth by collecting keys, avoiding obstacles and enemies.

#### The main elements:
- Player: First-Person View.
- Labyrinth: A simple structure of walls forming corridors.
- Keys: Several keys scattered around the labyrinth. The player needs to collect all the keys to unlock the exit.
- Obstacles: There should be traps or enemies in the labyrinth that the player must avoid.

#### The controls:
- Use `WASD` and arrow keys to move around.
- Use the `Mouse` to control the character's camera.
- Add the ability to run using the `Shift` key.

#### UI elements:
- Key counter: Shows the number of collected keys and the total
the number of keys needed to open the exit.
- Time counter: Displays the time the player spends to complete the labyrinth.
- Victory message: Displayed when the player has collected all the keys and found the exit. This message should have two buttons: restart the level and exit the game.
- Defeat message: If the player falls into a trap or collides with an enemy, a defeat message is displayed. This message should have two buttons: restart the level and exit the game.
- Pause window: If the player presses `ESC`, the game stops and a pause window is displayed. There should be two buttons in it: continue and exit the game.
- All texts must be made using `TextMesh Pro` and a custom font of your choice.

#### Additional requirements:
- Add sound effects for collecting keys, character steps, activating traps, and colliding with enemies.
- Add background music that you find on the Internet.

#### Hints:
- Game code must be written in `C#`.
- Add comments to the code in English.
- Follow the principles of clean code, `OOP` and `KISS`.
- Organize project files into appropriate folders.
- Name the project files in a clear and understandable way.
- Separate UI elements and game objects into different layers.
- Upload the project to your `GitHub`.

#### What we're looking at:
- Accuracy of task performance.
- Functionality of the game.
- Quality of written code.
- Organization of project files.
- UI quality and structure.
- General cleanliness of the project.
- Creativity and innovation.
- Deadline: up to 5 days.