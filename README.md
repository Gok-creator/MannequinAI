# MannequinAI (REPLICATED)
Mannequin NPC AI System for Horror Games

Bring spine-chilling experiences to your players with this advanced AI system, inspired by the terrifying behavior of Mannequin NPCs. Perfectly designed for horror games, this AI ensures an immersive and heart-pounding gameplay experience.

Key Features:
Realistic Enemy Behavior: The AI replicates the iconic mechanic where Mannequin NPCs stop moving when observed and pursue the player when unobserved, creating constant tension.
Strategic Stalking Mechanics: Players must carefully manage their line of sight to avoid being caught off-guard.
Multiplayer-Ready Design: The AI is optimized for multiplayer environments, ensuring synchronized behavior across all players.
Optimized for Performance: Seamlessly integrates into Unreal Engine projects without impacting performance.
Customizable and Modular: Easily adapt the AI's behavior to fit the unique needs of your game.
This AI system faithfully recreates the chilling behavior of Mannequin NPCs, making it an essential tool for developers aiming to craft unforgettable experiences in both single-player and multiplayer horror games.

How to Use:
Follow these steps to seamlessly integrate the Mannequin NPC AI System into your Unreal Engine project:

1. Add AI Perception and AC_Mannequin components to your character's blueprint.</br>
![Screenshot_20](https://github.com/user-attachments/assets/46217f84-59d8-42ee-821b-892cc42fff51)</br>
2. Call the On Target Perception Updated function to detect whether the player can see the AI or not, triggering the AI's response accordingly.</br>
![Screenshot_21](https://github.com/user-attachments/assets/c7ff846b-bc19-49c2-b7e0-52b04cb31c8f)</br>
3. Call the Is See Server event inside the AC_Mannequin component to handle the server-side check for visual perception of the AI.</br>
![Screenshot_22](https://github.com/user-attachments/assets/65f42f9d-702f-44e5-a90f-53906fce73ca)</br>
4.Inside the AI_Mannequin class, use the Get All Actors of Class node and replace it with your own character class.</br>
![Screenshot_24](https://github.com/user-attachments/assets/6ff0eb5b-6104-4005-b767-78e6e7563b21)

