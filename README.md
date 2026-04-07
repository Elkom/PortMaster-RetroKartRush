# Retro Kart Rush port for PortMaster
Retro Kart Rush is a retro racing game that will transport you back to the 16-bit era. Where friendships were made (or broken) by playing multiplayer games in front of the TV.

Available on [Steam](https://store.steampowered.com/app/1877000/Retro_Kart_Rush/) and [Itch.io](https://kurigamedev.itch.io/retro-kart-rush)

Disclaimer: I am not the game developer, I'm just getting the game to run on PortMaster compatible handheld devices!

## Known Issues
In the current state, the game crashes when any input is pressed.
As such, I am not sure which of the following will be the final game input emulator:
- [gptokeyb](https://github.com/EmuELEC/gptokeyb)
- [gptokeyb2](https://github.com/PortsMaster/gptokeyb2)

## About
This is my first time porting a game for PortMaster. The game is originally built with Godot 3.4.2.
Since the goal is to run this game on handheld devices, it requires [FRT](https://github.com/Cebion/frt.git).

I've built a FRT binary of the same version as was the game built with and it's located in the `runtime_3.4.2` directory. I've left it named as the build command put out.

The game can get up and running with both my runtime, and with the already available 3.4.5 runtime within PortMaster.

# Instructions
To run this game you need to buy the official game through either Steam or Itch.io. Download and copy `RetroKartRush.pck` to the `gamedata` directory.

## Thanks
- kurigamedev (Game Dev)
- (ToDo)