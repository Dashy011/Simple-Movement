Unity Player Movement Script
Overview
This is a first-person player movement script for Unity, featuring smooth movement, jumping, and camera control for looking around. The script uses Unity's Rigidbody-based physics to handle movement and jumping realistically while ensuring smooth camera rotation with mouse input.

Features
✅ Smooth Player Movement – Uses WASD or arrow keys for forward, backward, and side movement.
✅ Jumping Mechanic – Press Spacebar to jump when the player is on the ground.
✅ First-Person Camera Control – Move the mouse to look up, down, left, and right.
✅ Ground Check System – Prevents jumping in mid-air using a raycast.
✅ Adjustable Sensitivity & Speed – Easily modify movement speed, jump force, and mouse sensitivity in the Inspector.
✅ Cursor Locking – The mouse is locked in the center of the screen for a true first-person experience.

Setup & Usage
1. Add the Script to Your Player Object
Create a Player GameObject (e.g., a Capsule).
Attach a Rigidbody component to the Player.
Drag and attach this PlayerMovement.cs script to the Player.
Assign the Main Camera as the playerCamera in the Unity Inspector (it should be a child of the Player).
2. Adjust Variables in the Inspector
moveSpeed: Controls how fast the player moves.
jumpForce: Determines the height of the jump.
mouseSensitivity: Adjusts camera sensitivity.
groundCheckDistance: Defines how close the player needs to be to the ground to allow jumping.
3. Input Controls
W / Up Arrow → Move forward
S / Down Arrow → Move backward
A / Left Arrow → Move left
D / Right Arrow → Move right
Spacebar → Jump
Mouse Movement → Look around
Requirements
Unity 2020 or later
C# scripting knowledge (for modifications)
A 3D environment with collidable ground
Customization
Want to add sprinting, crouching, or other mechanics? You can modify the Move() function to change movement speed dynamically based on input.
