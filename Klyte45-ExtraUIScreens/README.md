# Extra UI Screens Mod
## _Use additional monitors_

This mod is designed to allow use any screen available in current PC to show other mods information. It also allows creating a new overlay over the game screen, both integrated with game and as a new separated layer (as it was an extra screen).

Modders can take advantage from this mod to create complexes UI, like report tables, map drawings or advanced mod setups. 

This mod is just a platform for other mods, it does almost nothing in the game alone.

## For mod creators

Check the base react project at my [GitHub](https://github.com/klyte45/EUIS-baseproj-fe) to get instructions about how to create a new frontend application into EUIS.

Soon will be available a base project for creating mods windows over the vanilla UI keeping the interactivity with vanilla UI.

Also there will have a way to add simple buttons to toggle tools in the vanilla UI in a dock group - like Unified UI (UUI) used to do in CS1. The mod window over vanilla UI explained above also will generate a button there.

Detailed tutorials soon!

## Feature roadmap
- ✅ Allow using extra monitors available as UI container for mods apps
- ✅ Allow selecting which app to be available each screen
- ✅ Allow creating a new layer over main screen (toggle using Ctrl+Tab when enabled)
- ✅ Allow each mod to create more than one app for different purpoises
- 🔜 Allow creating integrated apps in the main game UI
- 🔜 Allow creating a shortcut toolbox for tools like UUI did back in CS1
- 🔜 Allow have more than one app open in some screen
- ✅ Disponibilize basic project for modders to create apps in extra screens/main UI overlay
- 🔜 Disponibilize basic project for modders to create integrated apps to main UI

### Notice!
Cities Skylines 2 uses Coherent UI to emulate a simplified version of Chromium to render the game UI, so not all common web features are available to use in game UI. For more information check the [Coherent UI documentation](https://docs.coherent-labs.com/unity-gameface/)

## Experimental mod warning!
Since it's a very complex mod, it may cause issues in the game due their early stage of development. However, by the nature of this mod it's very unlikely it to break after game updates - but watch out the mods that may be using this mod as UI platform because they may be sensible to game updates.

## Known bugs
- The game always will startup on current resolution of monitor, despite the option selected up in game settings. If you use a different resolution in the game you will need to set up again every game session.
- When enabling a screen, you shall restart the game or the main game UI will not accept inputs.