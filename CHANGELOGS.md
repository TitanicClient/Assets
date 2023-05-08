# a370b37/open-beta
- Switched where the update checker was pulling information from.

# 17bb966/open-beta
- Small UI tweaks: resized the mod settings button to be a larger  button, as well as fixed the logo position in the settings menu, should be more consistent with the HUD editor's position now.

![image](https://user-images.githubusercontent.com/96212795/236837807-5ba6be63-9af4-4d63-ae53-d58806fadc1b.png)

# 00d9f57/open-beta
- Fixed an issue with category buttons deselecting when clicking outside the menu 

# 69f1880/open-beta
- Completely rebranded the accent color used across the UI, it should be better to look at
- Other small UI tweaks
- Removed the "Misc" category, as it was a duplicate of the "All" one

# 175991f/open-beta
- Updated screenshot on README
- Fixed an issue where categories would get unset when clicking on other buttons, this should not have happened.

# d70dae3/open-beta
- Changed the toggle setting icon from “X” to a checkmark icon
- Added mod categories at the top of the mod list for easier navigation
- Replaced the third party icon with an accurate one (Cave Story menu)
- Tweaked other button icons and sizes

# 7cf8a1e/beta
- Overhauled sliders, they now have an actual cursor instead of just filling the slider.
- Overhauled the Crosshair Editor mod, it's behavior has been completely changed and now allows the user to modify a custom crosshair by allowing an outline, changing the thickness, size & gap of the crosshair. This mod was also renamed to just "Crosshair"

# 9d4f1de/open-beta
- Brought back instantly updating skins, without the freezes and with skin caching now!
- Other general bug fixes for a1.1.2_01

# d423231/open-beta
- Added logo branding to Titanic related menus
- Fixed an issue with block breaking textures not appearing on a1.1.2_01
- Fixed an issue where certain entities would not render properly on a1.1.2_01

# 2c91142/open-beta
- Updated DiscordIPC library to TheKodeToad's fork, this fixes Discord RPC not working on Linux and newer versions of Java.

# 2dcf256/open-beta
- Fixed a Vanilla render engine issue with null textures.

# be96ecf/open-beta
- Updated the Server List menu to display a message if no featured servers were found for the version of the client.
- Branch name was changed from **beta** to **open-beta**

# b31a5b6/beta
- Added Alpha 1.1.2_01 support
- Fixed an issue with the ingame server list allowing you to go to the main menu

# bb899e6/beta
- Fixed automatic update checker false flags

# d6d7576/beta
- Omitted `/l` from chat history, as it does the same thing as `/login`
- Made the mod menu button only allow left mouse clicks
- Changed the friends keybind to `just Tab` for compatibility on other operating systems
- Made toggle chat a simple toggle setting instead of a keybind setting to prevent confusion.

# 044243f/beta
- Fixed double key presses in Titanic only menus
- Reimplemented performance related options
- Removed automatic positioning of mods, you can now freely move them off the screen if you'd like
- Temporarily reverted back to the other skin proxy because the instant implementation was causing FPS spikes

# 342eb96/beta
- Added Compass Mod

# b84245f/beta
- Added Facny Grass to b1.1_02 & a1.2.6

# cc992f8/beta
- Readded Alpha 1.2.6 support
- Made "Main Menu Logo" a Beta only feature

# b4302a7/beta
- Added Discord RPC Mod

# a6bceb9/beta
- Removed Hotbar mod until further notice.
- Fixed an issue where Crosshair Editor would cause the Vanilla hotbar to corrupt itself.
- Other various improvements, Multi Version support is coming soon.

# fb68783/beta
- Fixed texture positions with Smooth Lighting

# 6a9f6ba/beta
- Mostly moved everything to the new Bridge system, a few bugs may occur!
- Dropped a1.2.6 support for the time being, it will return in the near future
- Removed the lock feature for 3rd party mods, as it was essentially useless.
- Made the watermark only appear when paused and in the main menu.

# 713fce9/beta
- Added ingame texture packs button
- Fixed emote perspective being weird

# e710d64/beta
- Made it so you don't have to type in the color codes for player nicknames
- Added wave emotes for friends on supported servers (AlphaPlace for now)! Add them and type `:wave:` in chat, their player will then wave at you if in range
- General bug fixes

# fe7f0a0/beta
- Brings optimizations to player asset loading.

# 0552a1b/beta
- Brings a featured servers list.

# aeab200/beta
- Changes some stuff with auto login.

# ca7aee3/beta
- Started compiling with Java 8 instead of 11, forgot that legacy Minecraft runs on that.

# 09f389e/beta
- Added an automatic update checking system, when a new one is available, it will notify you in the bottom left where the commit watermark is.

# 285a250/beta
- Added an option to Chat Editor that hides ownership chat messages on AlwaysAlpha
- Reinstated cape position fixes for PlayerModelFix

# 0fc7545/beta
- Backported capes to a1.2.6

# 2748853/beta
- Added Alpha 1.2.6 support
- Fixed some issues regarding hotbar

# 7da9b54/beta
- First open beta build, bugs are expected
- Fixed an issue with chat history not working as intended
