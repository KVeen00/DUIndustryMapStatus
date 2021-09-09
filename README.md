# DUIndustryMapStatus
Dual Universe Industry Map Status

Why are you here?

1)You were given the link and asked to try it out: Welcome, see instructions below, please provide comments on Discord(KVeen#3678)

2)You searched for Dual Universe on GitHub: Welcome as well, but this code is not ready for general distribution. You can try it out by following the instructions below but it is currently in limited distribution for testing. A public release-has a long way to go. This is one component of a larger project but is in fully working condition for what it does. 

Installation Instructions:
1) Place a Programming Board on your static consruct, and 1 screen
3) Copy the entire block of code in the above files (view as "RAW)
4) In-game, right click on your Programming Board, select 'advanced' and then "Paste LUA Configuration from Clipboard"
5) In build mode, select your link tool, right click on the Programming board and link FROM the programming board to the core and 1 screen (use 'screen' NOT screen1)
6) Exit build mode and activate the programming board

Optional: You can edit LUA parameters and check or uncheck Industry filter. When checked ONLY industry units will be shown, when unchecked, all core elements will be shown.

**System behavior**

  1) When activated the board will identify all "Jammed" industry with a red dot on the map AND place a 3D sticker hovering over the industry at its location
  2) Checking/unchecking the 'industryfilter' in LUA parameters will show ONLY industry units (checked) or all elements (unchecked)
  3) The three map panels from the left are 'top view', 'front view', and 'side view' of your core. The white dot represents the core build zone center point
  4) The board is static it does NOT update in real time. It shows the state when activated and the stickers persist until the board is deactivated. If you need to refresh, simply de-activate and activate the board.
  
  **Planned**
  This is a small portion of a larger project but the visualization is not complete for the larger project using the new LUA screen renderer. A HUD version is planned to show a single view (top, side, front) in a small HUD so you can travel around looking for your misbehaving industry. If there is interest, that can be made to auto-update and possibly show player position in relation to the elements.
  
  
  **Known Issues**
  If you have many many many elements you can overload it. The will probably require several thousand elements. However, if you check the industry filter that will probably fix it. If you have enough industry units in a single large core to overload it....well my hat is off to you.
