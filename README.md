# SuperWackyFrogs
Source code of unfinished game "Super Wacky Frogs". Here's ![gameplay of the non-modified game.](https://github.com/SignorOmbra/SuperWackyFrogs/raw/main/docres/OriginalGame.mp4)

# Setup
Requires Flipper by Reselim. It's built in here, but I advise you use the latest version. ([Reselim/Flipper](https://github.com/reselim/flipper))

- Workspace
  - Music (Sound)
  - Spawns (Folder, Contains SpawnLocations)
  - ElevatorGround (BasePart, Used for lobby elevator.)
- ReplicatedStorage
  - Resources (Folder)
    - MusicList (Folder, Intermission music)
  - Values (Folder)
    - Failed (BoolValue)
    - Status (StringValue)
    - Time (StringValue)
- ServerStorage
  - Events (Folder, Event models)

## Example Event:
- EventRoot (Model, change name to event name)
  - EventMusic (Sound)
  - Map (Folder, Contains map parts)
  - Scripts (Folder, Contains map scripts)
  - Spawns (Model/Folder, Contains parts that act as SpawnLocations)
  - StartBox (Model/Folder, A box cleared when the event starts)
  - Metadata (Folder)
    - Depth (NumberValue/IntValue)
    - Instructions (StringValue)
    - LowerTime (IntValue)
    - Objective (StringValue)
    - Reward (NumberValue/IntValue, Unused and meant for currency)
    - Time (IntValue)
