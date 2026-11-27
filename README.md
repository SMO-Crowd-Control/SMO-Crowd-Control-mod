# Super Mario Odyssey Crowd Control

Play **Super Mario Odyssey Crowd Control**, and let Twitch viewers change the game with ingame events activated through Channel Points. This release has a game mod for Nintendo Switch and Ryujinx, plus a PC dashboard with the multiplayer server.

## Downloads

- **Mod.zip** — Nintendo Switch / Ryujinx game mod
- **PC.zip** — PC dashboard and bundled multiplayer server

## Community

- [Project website](https://smo-crowd-control.github.io/)
- [Discord server](https://discord.com/invite/4rK7TpA7Vu)

## Credits

- Secret Dev + Team for smoo+
- The SMO Decomp Team

### PC dashboard and server

1. Extract `PC.zip`; keep the `Dashboard` and `Server` folders together.
2. Install [Python 3](https://www.python.org/downloads/) and the [.NET 10](https://dotnet.microsoft.com/en-us/download/dotnet/10.0) Runtime.
3. From the extracted package folder, install dashboard dependencies by using this command:

   ```powershell
   py -3 -m pip install -r Dashboard/PC/requirements.txt
   ```

4. Run `Dashboard/START-DASHBOARD.cmd`, configure Twitch if you want Channel Point events, and start the server from the dashboard.
5. Connect the game eather through local IP or through an online Server.

## Installation

- You can find detailed Tutorials on our website

### Nintendo Switch

1. On a modded Switch with Atmosphere, extract `Mod.zip` to the root of the SD card.
2. Confirm the files are under `atmosphere/contents/0100000000010000/`.
3. Use Atmosphere with the game and start Super Mario Odyssey.

### Ryujinx

1. Enable the game's mod directory in Ryujinx.
2. Copy `exefs` and `romfs` from the title folder in `Mod.zip` into the game's mod directory.
3. Disable older SMOCC mod versions to avoid conflicts.

## Solo mode

- Connect one Switch directly to the PC dashboard; no multiplayer server or online room is needed.
- Put the PC and Switch on the same network, choose **Solo** in the dashboard, enter the Switch IP address and port, then select **Connect Switch**.
- Connect a Twitch account and start Crowd Control to enable Channel Point events. Use the dashboard to configure or test events and watch redemptions, delivery status and errors in the activity log.

## Online multiplayer

- Join the public room or create a named, password-protected room. Browse rooms, preview players and set player limits.
- See online players' names, platform, region, status and ping. In-game nametags and map markers help locate players in the same kingdom.
- Synchronize player and Cappy positions, coins, collectibles, moons, checkpoints and moon rocks. Sync options can be changed, and joining players can catch up on room progress. Deathlink and persistent moon progress are also supported.
- Chat in-game or through the dashboard. Send public messages or private whispers.
- Use the experimental spectator mode to follow a player, visit kingdoms or explore with a free camera. Spectators do not appear in normal player lists and are excluded from gameplay sync and event targets.

The dashboard can start and monitor the server, connect the game, manage rooms and players, kick players, move them to a selected kingdom, send/test events and show event activity.  In-game menus provide network, gameplay and Crowd Control settings, an event guide, player/event status, ping indicators, speedrun and Non-Stop options, and custom UI and icons.

## Warning

- This Mod only works on verson 1.0 of the Game
- The Event "Random Warp" has a bug, where it crashes the game 50% of the Time (so dont use it)

## Events

- Jump
- Auto Jump
- Disable Jump
- Crouch
- Cap
- No Cappy
- Auto Cappy
- No Cappy Jump
- Infinite Cap Jumps
- Reversed Joysticks
- Random Inputs
- Random Speed
- Random Size
- Random Jump Height
- Swap Positions
- Moon Gravity
- Random Gravity
- No Oxygen
- Wind Gust
- Ice Floor
- Floor Is Lava
- Underwater World
- Rocket Flower
- Give Coins
- Remove Coins
- Gift Moon
- Steal Moon
- Random Stage
- No Checkpoints
- No Captures
- Invincible
- One Heart
- Kill Mario
- First Person
- Invisible Mario
- No HUD
- Random Outfit
- Goomba Ring
- Spiny Ring
- Change Music
- Random Filter
- Inverted Colors
- Upside-Down Camera
- Green Demon
- Random Effect
