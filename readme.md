# Simple Game Unreal Engine 5.3.2

This game based on gorka games tutorial and I modified some of it. It includes some basic thing like walking locomotion, wave spawner, etc. Build using UE 5.3.2

# Screenshots

![](https://github.com/ydhnwb/fps_simple_game/blob/main/Screenshot1.png)  
![](https://github.com/ydhnwb/fps_simple_game/blob/main/Screenshot2.png)

# Experience

I noticed that Wave Spawner blueprint and its public variables (Spawn Location) is relative to its parent location.
So it is not in the world location, please be aware of it. \*added to my personal notes notion

# Git LFS

This also my first time using LFS. Kindly to reuse the .gitattributes file to make it work on push and also create .gitignore template when creating new repository.

# Note to improve

AI to move and rush for player kinda not optimized (it often not looking to the player when it very close), just need to update the rotation to the player before attack calculation.
