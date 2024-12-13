# Portable TV Screen 1.4 (Easy Installation)
This portable screen allows you to watch whatever is playing on the video player directly in front of you, eliminating the need to hold a tablet or look at your camera's interface. You can also drop the screen in the world, choose between a local and a remote toggle, change the scale and distance, and overlay it over players and the world. If there are multiple portable screens and the local player is active, it will disable all remote instances if it gets too close, but only for you.

This asset was mainly created for **Popcorn Palace** and **Illumination Media Player**, but it works in other maps too that support the Global Render Texture.

**⚠ This asset will only work if the video player is broadcasting a UdonVideoTex Global Render Texture in the instance.**

## Info
- 20 Bits of Synced Bits
- 1 Material Slot
- 4 Verts
- 4 Parent Constraints
- 2 Contacts
- 6 Layers (In a release version they might be compressed, but since VRCFury is required anyway, I would recommend using the Direct Tree Optimizer.)

## Test Avatar
If you want to test the asset before installing it on your avatar, here is a public test model: https://vrchat.com/home/avatar/avtr_641411e5-a2dc-47b1-851a-56da450e235d

## Requirements
- VRCFury's latest version (https://vrcfury.com)
- at least Poi 9.1.7 Toon (free version: https://www.poiyomi.com/download) or Pro version

## Controls
- **Turn On**: Toggles the screen on for you and everyone else that has your avi shown.

- **Turn On (Local)**: Toggles the screen on only for you.

- **Drop in World**: Drops the screen in the world where it is at the time. (if someone loads your avi after the screen has been dropped, it won't be in the same location)

- **Scale**: Increase the size of the screen.

- **Distance**: Move the screen further away from its origin.

- **Overlay mode**: Changes the screen so it will render over most objects like walls and avatars. (If you encounter any issues with this, like avatar assets rendering on top of the screen, please let me know in what way.)

- **Lock To Head**: Locks the screen to the head. If this is turned off, it will be locked to the hand.

## Installation
1. Install the required packages.

2. Import the TVScreen_1.4 package.

3. In the Project tab under Assets>TvScreen, you will find the TVScreen NotSynced prefab.

4. Drag and drop this prefab onto the root of your avatar.

5. Open the TVScreen prefab and adjust the HeadMount in the Y direction until it meets your eye height.

6. (**optional**) If you want to change the menu location to a different submenu,

   - Select the TVScreen component on your avatar; this should show it in the Inspector.

   - Click Edit in Prefab at the top right on the Full Controller component.

   - Then under Menu > Prefix, add your prefix behind the screen like this: YourMenu1/YourMenu2
