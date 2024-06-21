# **Changelogs**

This page shows all the changelogs from JourneyMap 6.0.0 which is the latest version of JourneyMap so far.

## JourneyMap 6.0.0 Beta 8

- Fixed: Issue when disabling worldId.
- Fixed: Teleporting to nether from overworld being off.

## JourneyMap 6.0.0 Beta 7

- Fixed: More waypoint issues with the nether

## JourneyMap 6.0.0 Beta 6

- Fixed: Servers unable to create config files, due to Mojang changing how getServerDirectory() works.
- Fixed: Map Filters/Shaders halting mod loading on Linux.

## JourneyMap 6.0.0 Beta 5

- Fixed: Existing waypoints rendering in the wrong location in the nether.
- Added: Highlight on primary dimension in the waypoint editor.
- Changed: Hide Fullscreen Buttons and Toggle Waypoint Rendering keys default to unbound.

## JourneyMap 6.0.0 Beta 4

- Fixed: Some waypoint oddness in the nether.
- Fixed: Entity Icons not displaying after being set by API.
- Small API update

## JourneyMap 6.0.0 Beta 3

- Fixed: Crash when saving/removing waypoints when connected to a vanilla/spigot server

## JourneyMap 6.0.0 Beta 2

- Fixed: Inventory Hud+ conflict
- Fixed: Re-added mod menu support.
- Fixed: [Fabric] issues with ImmediatelyFast

## JourneyMap 6.0.0 Beta 1

- Major Change: The Web Map has been split into its own mod.
- API Version 2.0 required
- Added: WIP New Waypoint Manager with Groups. This changes how waypoints are saved.
- Added: Map Filters: Several Sepia variations, and gray scale.
- Added: ColorPalette editing user interface, button in fullscreen map.
- Added: New theme selection to fullscreen map.
- Added: Advanced Config option to disable player icon fading based on vertical distance.
- Added: Server option to fully disable cross dimension waypoint teleporting.
- Added: Config setting for entity label colors(journeymap.core.config).
- Added: [Fabric] ModMenu Support
- Added: New Cartography option to disable shadows on the map.
- Added: Legacy Themes -> Vault, Victorian, and Flat Vault
- Added: Buttons to copy options from minimaps and fullscreen.
- Added: Options for displaying entity names of all types. Fullscreen Default:Enabled, Minimap Default:Disabled, Hotkey for toggle in FS and MM Default:G, Hold Tab for Quick Display of names and icons.
- Added: Far Zoom Out. Minimap will zoom out one extra tick. Fullscreen map will zoom out very far!
- Added: MemeSapiens to developer in splash screen.
- Added: Map Type selection in minimap!
- Added: New Info Slot options: Movement Speed, Current Weather
- Added: Waypoint manager sorting is now saved, so it retains the sort on minecraft restart.
- Added: Textures to the PolygonOverlay.
- Added: Tooltips to dropdown menu items.
- Added: MiniMap now draws behind all screens.
- Added: Option to also save map by IP
- Added: Fullscreen Menu Option -> Advanced -> Delete Region
- Added: Show Ambient Creatures on the map. Option in Advanced for count, name display. Server will disable these with animal radar. [Default: False]
- Added: Cartography Option for Auto Cave Mode Threshold. How many blocks above player before switching to cave mode.
- Added: New entity icon display mode: Dots and Icons. It has an outline that gives more contrast to the icons.
- Added: Option to change the font scale of info slots.
- Added: Surface, topo and biome mapping to The Nether.
- Added: Keybind for following the player in the fullscreen map. [Default: F]
- Added: Color Palette Screen to edit block colors, by world or globally.
- Updated: AutoMap missing, will now also map partial regions.
- Updated: JourneyMap now uses SemVer versioning.
- Updated: Moved some options from Waypoint Beacon options to the Waypoint section.
- Updated: Infoslot dropdowns are sorted.
- Updated: Long dimension names over 25 characters are compressed.
- Changed: Defaults: Purist Theme, Mob Icons with outlines
- Changed: Disabling by server is less severe, no longer requires client restart to use JM in singleplayer after server disables JM.
- Changed: Disable Waypoint KeyBind now only disables rendering, does not set the waypoint to disabled.
- Changed: MiniMap is now draggable in Preview Mode in the OptionsScreen.
- Changed: Mouse Wheel zooms in and out on mouse location in the Fullscreen Map.
- Changed: Better sorting for options in fullscreen and minimap options, so they are consistent in order.
- Changed: Zooming in and out in follow mode keeps player as center. When not on follow, it uses mouse as center.
- Changed: Dramatically reduced render calls.
- Changed: Waypoint beacon icon and label under the crosshairs is displayed in front of the others.
- Updated: Made it a bit more clear when render distance is synced to Minecraft's Render Distance
- Updated: Player location now uses the player camera, this provides support for mods that add free cameras.
- Updated: Hide fullscreen map buttons keeps them hidden until you manually enabled them via hot key or restart minecraft.
- Updated: Info Slot text will draw font shadow if the background alpha is less than .05 to enhance visibility.
- Updated: Added timeouts for fetching player skins.
- Mod Compat: Create Mod Curved Rails not rendering and Railway Casing color.
- Mod Compat: ChinjufuMod leaves not rendering correctly.
- Mod Compat: Support Cobblemon resource packs.
- Fixed: Default water colors when mods break it.
- Fixed: Quilt file protocol.
- Fixed: API Markers text offsets.
- Fixed: Fake players causing issues with icon retrieval.
- Fixed: Theme Toolbars not using images properly.
- Fixed: Options not displaying tooltips.
- Fixed: Bad chunks breaking cave mapping.
- Fixed: Logs displaying what is under them in caves.
- Fixed: More tree and plants added to topo ignore.
- Fixed: Game unpausing when opening a dropdown or popup menu.
- Fixed: Crash when api removes non polygons.
- Fixed: Possible rare crash when creating a new UIState fails.
- Fixed: Bed block rendering.
- Fixed: Weird modded villager names.
- Fixed: Topo map randomly changing colors.
- Fixed: Client Render range larger than Server causing chunks to render black.
- Fixed: Slopes at 0 and below.
- Fixed: Expanded Radar when day/night cycle is disabled.
- Fixed: Shaky text in map labels.
- Fixed: Long standing bug when zoomed in and dragging the map it is choppy.
- Fixed: Removed some unnecessary class allocations that can have a severe impact on performance
