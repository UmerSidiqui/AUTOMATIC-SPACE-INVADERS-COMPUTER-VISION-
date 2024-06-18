Space Shooter Gesture Control
This project implements a space shooter game controlled using hand gestures detected through a webcam. The player's spaceship movement and shooting are controlled by specific gestures recognized using the Mediapipe library for hand tracking. The game features enemy spaceships that move downward while shooting at the player, who must dodge enemy fire and eliminate opponents to advance levels.

Key Features:

Hand Gesture Control: Use hand gestures detected from webcam feed to move the player's spaceship and shoot lasers.

Enemy Spaceships: Various enemy types with different behaviors and health levels.

Health and Lives: Player has limited health and lives; losing all lives results in a game over.

Level Progression: Advance through levels by defeating waves of enemy spaceships.


Technologies Used:

Python: Programming language used for game logic and gesture recognition.
Pygame: Library for game development in Python, used for graphics and game mechanics.
OpenCV: Library for computer vision tasks, used for webcam input and image processing.
Mediapipe: Machine learning library by Google for hand tracking and landmark detection.

How to Run:
Clone the repository to your local machine.
Install the necessary Python dependencies (pygame, opencv-python, mediapipe).
Run main.py to start the game. Ensure your webcam is connected and positioned correctly.

Future Improvements:
Implement more complex gestures for additional gameplay mechanics.
Enhance enemy AI and behavior patterns.
Add sound effects and background music.
Improve UI and add more visual effects.
