# Project Rebirth — Installation Guide

## Requirements

- Call of Duty 4: Modern Warfare (PC)
- A text editor, such as Visual Studio Code
- A CFG file from Project Rebirth

## Installation

**1. Locate your COD4 installation directory.**

For a Steam installation, this is typically:

`...\Steam\steamapps\common\Call of Duty 4\`

**2. Open the `main` folder.**

This folder contains game data and can be used to store our custom CFG files.

**3. Copy `rebirth.cfg` into the `main` folder.**

Example:

`...\Call of Duty 4\main\rebirth.cfg`

**4. Launch COD4 Multiplayer.**

Enable the developer console in the game's options if it isn't already enabled.

**5. Start a private match.**

Open the console using the tilde (`~`) key.

**6. Execute the CFG.**

Enter:

`/exec rebirth.cfg`

Press Enter.

## Verification

Build 001 contains the command:

`say Hello World`

If the installation is successful, the message should appear in the in-game chat.

**Tested:** Build 001 successfully executed in COD4 Multiplayer.

## Troubleshooting

If the CFG doesn't execute:

- Confirm the filename ends in `.cfg`, not `.cfg.txt`.
- Check that the file is in the correct `main` folder.
- Verify the filename matches the `/exec` command.
- Check the developer console for errors.

## Notes

Project Rebirth is currently an experimental CFG project intended for private-match testing.

Later builds may require additional installation steps.
