# Necromancy Mod

This mod adds necromantic abilities to Cataclysm: Dark Days Ahead, allowing players to resurrect killed creatures as loyal undead minions.

## Features

- **Corpse Resurrection**: Resurrect any unpulped corpse as an undead minion
- **Stat Preservation**: Resurrected creatures retain their original stats and abilities
- **Pet AI**: Undead minions use the same AI as tamed animals for following and commands
- **Necromancy Skill**: New skill tree for necromantic abilities
- **Management Commands**: Control your minions with follow/stay commands
- **Necromancer Profession**: Start the game as a necromancer with basic knowledge

## How to Use

1. **Learn Necromancy**: Start as a necromancer profession or find a Tome of Necromancy
2. **Find Corpses**: Look for unpulped corpses of creatures you've killed
3. **Examine Corpses**: Use the examine action (e) on corpses to resurrect them
4. **Command Minions**: Use spells to command your undead to follow or stay
5. **Manage Your Army**: Feed and interact with your undead minions

## Requirements

- Necromancy skill level 1+ to resurrect corpses
- Sufficient stamina (200+ points) for resurrection rituals
- Unpulped corpses (avoid using pulping attacks or butchering)

## Gameplay Balance

- Resurrection costs stamina and causes temporary exhaustion
- Higher necromancy skill allows more powerful resurrections
- Undead minions require occasional feeding with flesh
- Minions can be lost if they take too much damage

## Technical Details

This mod leverages existing game systems:
- Uses the built-in `revive_corpse` function to preserve original stats
- Employs pet AI flags (`CANPLAY`, `PET_MOUNTABLE`) for following behavior
- Integrates with the examine action system for corpse interaction
- Follows established patterns from Magiclysm and Tamable_Wildlife mods
