# Block Display Studio
A 3D editor and command generator for Minecraft block display entities.

![](Screenshot_20230611_134122.png)

[Try it now](https://eszesbalint.github.io/bdstudio)

## Beta 1.1.1 Changes
- New duplicates and new groups are selected automatically
- Setting scale to 0 no longer causes NaN values
- All blocks with rotated elements in them now render porperly (mostly affects plants and rails)
- Fixed texturing issues of blocks with animated textures
- Removed unloadable blockstates (chests, signs, banners, skulls... etc)

## Beta 1.1 Changes
- Updated for Minecraft 1.20
- Added Undo / Redo functionality
- Faster loading
- Added multi-level grouping and editing
- Collections can be named now
- Additional NBT tags can be inserted for block displays and collections (block displays will inherit the collection's NBT tags)
- Improved rendering of transparent objects
- Projects can be named now
- Added loading animation
- Long commands are now broken up into several commands to respect Minecraft's command length limit of 32500