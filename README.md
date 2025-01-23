# MannequinAI (REPLICATED)
Mannequin NPC AI System for Horror Games</br></br>

<h1>Purchase Link</h1>
Get the Mannequin NPC AI System here:</br>

Bring spine-chilling experiences to your players with this advanced AI system, inspired by the terrifying behavior of Mannequin NPCs. Perfectly designed for horror games, this AI ensures an immersive and heart-pounding gameplay experience.

<h1>Key Features</h1>
Realistic Enemy Behavior: The AI replicates the iconic mechanic where Mannequin NPCs stop moving when observed and pursue the player when unobserved, creating constant tension.
Strategic Stalking Mechanics: Players must carefully manage their line of sight to avoid being caught off-guard.
Multiplayer-Ready Design: The AI is optimized for multiplayer environments, ensuring synchronized behavior across all players.
Optimized for Performance: Seamlessly integrates into Unreal Engine projects without impacting performance.
Customizable and Modular: Easily adapt the AI's behavior to fit the unique needs of your game.
This AI system faithfully recreates the chilling behavior of Mannequin NPCs, making it an essential tool for developers aiming to craft unforgettable experiences in both single-player and multiplayer horror games.

<h1>How to Use</h1>
Follow these steps to seamlessly integrate the Mannequin NPC AI System into your Unreal Engine project:

1. Add AI Perception and AC_Mannequin components to your character's blueprint.</br>
![Screenshot_20](https://github.com/user-attachments/assets/46217f84-59d8-42ee-821b-892cc42fff51)</br>
2. Call the On Target Perception Updated function to detect whether the player can see the AI or not, triggering the AI's response accordingly. In the AI Perception settings of your character, adjust the Peripheral Vision Half Angle to 45 degrees to match the player's camera angle.</br>
![Screenshot_21](https://github.com/user-attachments/assets/c7ff846b-bc19-49c2-b7e0-52b04cb31c8f)</br>
![Screenshot_26](https://github.com/user-attachments/assets/a61ae6cf-9ae0-465f-bf6b-6f02f5e2190d)</br>

3. Call the Is See Server event inside the AC_Mannequin component to handle the server-side check for visual perception of the AI.</br>
![Screenshot_22](https://github.com/user-attachments/assets/65f42f9d-702f-44e5-a90f-53906fce73ca)</br>
4.Inside the AI_Mannequin class, use the Get All Actors of Class node and replace it with your own character class.</br>
![Screenshot_24](https://github.com/user-attachments/assets/6ff0eb5b-6104-4005-b767-78e6e7563b21)

<h1>Follow & Contact</h1>
Follow me on Instagram for more updates: tos.creative.studio</br></br>
For inquiries or issues, feel free to contact me at: korkutdilek@outlook.com</br>
