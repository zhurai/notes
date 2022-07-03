
# Interface Notes
## User Interface
- "Project Window" is where all the assets are located
- Rotation Tool: 
  - x = red
  - y = green
  - z = blue
## Editor Controls
- change view angle: alt/option + left click + move cursor
- zoom: trackpad/scroll wheel/hold alt button

# Editor Versioning Notes
- End of the version (e.g. **2021.2.6f1**)
  - Alpha = a
  - Beta = b
  - Candidate for final release = rc
  - Final release = f
- Ideally use LTS + final releases

# Term Notes
- Real Time - real time rendering
- Game Engine - point of convergence for all ingredients for creating a game (3D Models, Textures, Audio, Scripts, Animation, 2D Sprites, etc)
  - games: creator designs gameplay
  - animation: creator devises the animation being recorded
  - VR architectural visualization: creator builds the environment
  - DOES NOT: do 3D creation, 2D creation, audio creation, IDE type work
  - Note: Creators of Unity consider it now a "Real-time engine", not just a game engine
- Simple GameObjects - Cube/Sphere/etc

# General Editor Notes
## Default Objects
- main camera - controls what the player sees during gameplay
- directional light - simulates the sun (provides light that reflects off 3D GameObjects
## Parts of Game Objects
- shown in inspector
- separated by Components associated with said objects
- Unity uses a **Y-up coordinate system**
  - y = vertical plane
  - x/z = horizontal plane
## Notes on GameObjects
- Good practice: create **empty** gameObject as a placeholder/container for other GameObjects (for a more complex object) 
- can make GameObjects the child of the other (making any transform/etc applied to the child GameObjects as well)
## Directional Light 
- rotate to change
- position/scale options do not affect the directional light
- color changes the color of the light (not the sky)
## Types of Components
- Transform - location/rotation/scale
- RigidBody - give Object physical properties (for gravity/other GameObjects) 
- Materials - defines the surface characteristics of objects (change visual appearance)
- Physic Material - give Object more physical characteristics (bouncing, friction, drag, etc) **does not change visual properties**

# Sources
- https://learn.unity.com/tutorial/get-ready-for-unity-essentials
- https://learn.unity.com/tutorial/welcome-to-unity-essentials-1
- https://learn.unity.com/tutorial/get-started-with-the-unity-hub
- https://learn.unity.com/tutorial/get-started-in-the-unity-editor
- https://learn.unity.com/tutorial/what-is-real-time
- https://learn.unity.com/tutorial/what-is-unity
- https://learn.unity.com/tutorial/what-can-unity-do
- https://learn.unity.com/tutorial/who-are-real-time-creators
- https://learn.unity.com/tutorial/work-with-gameobjects-in-a-3d-scene
- https://learn.unity.com/tutorial/create-a-structure-with-primitives
- https://learn.unity.com/tutorial/add-components-to-3d-gameobjects
- https://learn.unity.com/tutorial/create-effects-for-3d-gameobjects

