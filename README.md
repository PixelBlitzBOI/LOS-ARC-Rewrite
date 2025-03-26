# Legacy Of Solaris ARC Rewrite
This repository is for the LOS ARC files rewrite which contains modified files from the xenon directory from LOS rewritten for expanded modding compatibility
![](art/icon.png)
# System
## Documentation
- [player.arc](#player.arc)
## player.arc
The player.arc file now has new folders for each playable character's lub files containing different lub files for different actions.
Note that if you want to make a mod for Tails or that changes anything related to [tails.lub](xenon/archives/player/xenon/player/tails.lub) or his [/tails](xenon/archives/player/xenon/player/tails) directory, you need to have the [Patch.mlua](Patch.mlua) file to fix the P06 Tail Spin Patch not operating correclty.
Some characters with similar proprieties (such as Rouge and Knuckles) might share the same .lub files from one of their directories. (An example would be how [rouge.lub](xenon/archives/player/xenon/player/rouge.lub) calls out [player/knuckles/knuckles-state.lub](xenon/archives/player/xenon/player/knuckles/knuckles-state.lub) for gliding and climbing parameters.)
