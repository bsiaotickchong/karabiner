# karabiner
Personal Karabiner config to share across devices

## Installation
1. Clone the repository locally into ~/.config/
2. Install Karabiner

## Karabiner
1. Install Karabiner
2. Open Karabiner-Elements
3. Open "Complex Modifications"
4. Add rule
5. Enable all

## How this works
Karabiner looks in `~/.config/karabiner/assets/complex_modifications/` for any json files.
These files then show up in Karabiner-Elements for the user to enable.
Upon enabling, they get added to the root-level `karabiner.json` file.
`karabiner.json` should not be manually edited.

## HHKB (JIS)
The hhkb.json is meant to be used in JIS-layout keyboards. Specifically, this adds helpful keybinds and macros that are intended for HHKB's JIS layout.
