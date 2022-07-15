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
- orbit (360 rotation): click alt button and hand button and hold
## Editor Versioning Notes
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
- Prefab - acts as a template of GameObjects
- Instances - copies of prefabs
## Directional Light 
- rotate to change
- position/scale options do not affect the directional light
- color changes the color of the light (not the sky)
## Types of Components
- Transform - location/rotation/scale
- RigidBody - give Object physical properties (for gravity/other GameObjects) 
- Materials - defines the surface characteristics of objects (change visual appearance)
- Physic Material - give Object more physical characteristics (bouncing, friction, drag, etc) **does not change visual properties**
- Audio Source - plays audio (edit AudioClip option to change the exact sound/music file)
- Audio Listener - recieves output from Audio Source (each scene can have only 1 Audio Listener)
## Prefab Notes
- In Hierarchy, prefabs are shown as blue
- Override prefab (e.g. for variants): edit it without going into prefab mode
- Creating variants: drag edited version into Project folder (pick "Prefab Variants" when asked)
- Prefab Variants seems similar to object inheritence in programming
  - if you edit something in the first/original prefab that is not an overrided component/value in the variants, then it will change the variants too
- can nest prefabs within other prefabs (when an object needs to be part of another)
  - e.g. a Tree with fruits (with multiple different fruits)
  - acts like a more complex GameObject (attached together), unless the individual prefabs have their own Physic Material
## Audio Notes
- Background Music:  
  - GameObject with Audio Source component
  - Add a sound to AudioClip option in component
- 3D Sound:
  - Spatial Blend: Move this all the way to the value of `1`
  - Min/Max Distance: How many units away the player will hear the 3D Sound (represented by a blue sphere)
# Scripting Notes
## Initialization
- created class extends MonoBehaviour
- contains 2 functions
  - `void Start()` - called once at the beginning of the game 
  - `void Update()` - called every frame of the game
## Unity Functions
- `Debug.Log()` - Logging data to console
- `Time.deltaTime` - interval in sections from last frame to the current frame
## Unity/C# Language Functions
- variable definition
  - \[public/private\] \[variabletype(e.g. string)\] \[variable name\] 
- variable types
  - `string`
  - `Vector3` - datatype for holding 3 values
- accessing components
  - adding `transform.localScale` to `Update()`
    - references the transform component of the GameObject of the script
    - seems to implicitly do this without a `self.` that one would do in other languages to refer to the current object...  
    - (whereas if you were to refer to another object you would make a variable and then do ``otherobject.transform.localScale`` to refer to that one from what I understand looking at https://docs.unity3d.com/ScriptReference/GameObject.html)

# 2D Editor Notes
- Unity uses a y = up system
- z is toward/away from the player's view in 2D 
  - changes in scale in the Z direction are not visible to the player

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
- https://learn.unity.com/tutorial/manage-gameobjects-with-prefabs
- https://learn.unity.com/tutorial/get-3d-assets
- https://learn.unity.com/tutorial/get-started-with-scripts
- https://learn.unity.com/tutorial/code-in-the-default-script
- https://learn.unity.com/tutorial/change-a-gameobject-with-script
- https://learn.unity.com/project/essentials-of-real-time-audio
- https://learn.unity.com/tutorial/add-background-music
- https://learn.unity.com/tutorial/create-real-time-3d-audio-effects
- https://learn.unity.com/tutorial/get-audio-assets
- https://learn.unity.com/project/essentials-of-real-time-2d
- https://learn.unity.com/tutorial/work-with-gameobjects-in-a-2d-scene
- https://learn.unity.com/tutorial/add-components-to-2d-gameobjects
- https://learn.unity.com/tutorial/get-2d-assets
