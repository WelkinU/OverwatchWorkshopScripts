# OverwatchWorkshopScripts

## Doomfist Pioneer Parkour
Version of Doomfist Parkour that lets users create their own checkpoints. Has improved key bindings, and features for multiple effect locks, pioneer route replay, downwards diag detection, tiny/massive player sizings, multi-hero support, map saving, off-map shenanigans and more. Based on the original version by kaeku (code X8080).

| Map | Workshop Code
| :- | :- |
| [Doomfist Pioneer Parkour](DoomfistParkour/DoomPioneerParkour.txt) | WARMR (Also YMVCR) |

## Ana Nade Trainer

Learn preset nade spots for Ana on most maps. Also has feature that lets you set a destination and the workshop auto-calculates throw angle to that destination from any other spot.

| Map | Workshop Code
| :- | :- |
| Ana Nade Trainer | 2Y555 |

## Doomfist Parkour Maps

Navigate Doomfist to the next checkpoint by using the abilities available to you.

| Map | Workshop Code | Comments
| :- | :- | :- |
| [Illios](DoomfistParkour/DoomParkourIllios.txt) | 7RDMK | 14 Levels, 180+ Checkpoints |
| [Busan Stadium (Lucioball)](DoomfistParkour/DoomParkourBusanStadium.txt) | HBE4T | 5 Levels, Only Available During Summer Games Event |


## Doomfist Parkour Multi-Hero Maps
| Map | Workshop Code | Heros | Comments |
| :- | :- | :- | :- |
| [Rialto](DoomfistParkour/MultiHeroParkourRialto.txt) | VP3H4 | Doomfist, Roadhog, Ana, Moira | 20 Levels, 4 Levels For Each Hero, Doomfist has extra cool levels. Framework also supports Winston and Sigma |


## Doomfist Rollouts
Eliminate the enemy hero within 4 seconds to advance to the next checkpoint! On more difficult levels, the enemy heros will defend themselves! Practice and peedrun Doomfist Rollouts on the map King's Row.

| Map | Workshop Code |
| :- | :- |
| [Kings Row](DoomfistParkour/DoomfistRolloutsKingsRow_1_0_0.txt) | TEATW | 


## Special Workshop Tools
Run these HTML files in a web browser. (Need Javascript enabled)

| Script | Description |
| --- | --- |
| [Workshop Merger](workshop_merger.html) | Merge one workshop into another. Handles merging of rules, variables, and subroutines. Example usage would be to merge a small testing workshop into a larger workshop.
| [Code Finder (Experimental)](code_finder.html) | If you have a list of Workshop Codes, this finds codes similar to a phrase you enter. For example, entering "Tower Defense" with the default codes suggests TP0WR as the best match. Uses the SIFT4 algorithm to match.


## Extra Cut-Paste Workshop Scripts
These are workshops with rules intended to be pasted into other scripts. These are located in the utils folder.
| Map | Description |
| :- | :- |
| Skybox Detector | Detect if a player is on the skybox and make them fall through it. Originally used as a map-agnostic solution for Ana parkour/pioneer |
| [MrDestructoBot](utils/DestroyMapRailings.txt) | Use the MsDestructo Bot from my Doom Pioneer map (Code: WARMR), its the most compact and fastest runtime...~~Obsoleted by [MsDestructo Bot](https://discord.com/channels/689587520496730129/757303228021866606/851573753698975755) with giant dva ult - much more compact as no railing data is needed. Creates a bot that very quickly destroys all map railings. This workshop includes railing data for all relevant maps. [Map data](https://nebulaow.github.io/MrDestructo-Data) from nebulaOW~~ |
| Multi-hero Wheel Select Menu | In-world custom hero selection menu. See [README.md](utils/README.md) |
| In-Game Keyboard | Creates an in-world keyboard for the user. See [README.md](utils/README.md) |



