# Legacy Of Solaris ARC Rewrite
This repository is for the LOS ARC files rewrite which contains modified files from the xenon directory from LOS rewritten for expanded modding compatibility
![](art/icon.png)
# System
## Documentation
- [player.arc](#playerarc)
- [Current Version](#current-version)
## player.arc
The player.arc file now has new folders for each playable character's lub files containing different lub files for different actions.
Note that if you want to make a mod for Tails or that changes anything related to [tails.lub](xenon/archives/player/xenon/player/tails.lub) or his [/tails](xenon/archives/player/xenon/player/tails) directory, you need to have the [Patch.mlua](Patch.mlua) file to fix the P06 Tail Spin Patch not operating correclty.
Some characters with similar proprieties (such as Rouge and Knuckles) might share the same .lub files from one of their directories. (An example would be how [rouge.lub](xenon/archives/player/xenon/player/rouge.lub) calls out [player/knuckles/knuckles-state.lub](xenon/archives/player/xenon/player/knuckles/knuckles-state.lub) for gliding and climbing parameters.)
**PLEASE MAKE SURE THAT WHEN MAKING MODS USING THIS THAT YOU ALWAYS LIST WHICH VERSION OF THE MOD AND WHICH VERSION OF LOS YOU MADE THIS FOR!!**
### Current Version:
1.0.0 (for LOS 2025/03/25)
