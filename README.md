# Unity 2D Movement Prototype

A Unity project containing a player movement and jumping script, animation assets, camera scripts, and a sample scene.

## Included source

- `NewBehaviourScript.cs`: horizontal movement, jumping, ground checks, sprite direction, and animation parameter updates.
- `CameraFollow.cs` and `CameraZoom.cs`: camera scripts.
- Animation assets for idle, running, jumping, and falling.
- `Assets/Scenes/SampleScene.unity`: sample scene.

## Open the project

1. Install Unity Hub and Unity Editor **2021.3.10f1**, the version recorded in `ProjectSettings/ProjectVersion.txt`.
2. Add the `My project (1)` directory as an existing project in Unity Hub.
3. Open `Assets/Scenes/SampleScene.unity`.
4. Inspect the player components and Inspector bindings, then enter Play mode.

Movement keys are configurable through the script's `L`, `R`, and `Spacebar` fields. Check the Inspector assignments before playing.

## Status and next steps

This repository documents a prototype; a finished game or playable release has not been verified.

- Add a gameplay screenshot or recording.
- Document scene setup and controls.
- Rename the generic movement script and project folder carefully, preserving Unity references.
- Verify the scene in the recorded editor version.
- Document asset sources, licensing, and individual contributions before distributing a build.
