# CHANGELOG

## 2.0.dev11
- Little fix for messages
- Fix for excess choosen
- Add messages.sp to scripting folder
- Fix alive spectator
- Add cvar for enable changing suicide attacker.

## 2.0.dev10
- Little fix in respawn timer
- Little fix for disconenct players (remove error in logs, but not fix problem)
- Change event names
- Little config change
- round_start and round_end now EventHookMode_PostNoCopy
- Make code more clear (add DRPrintToChat and DRPrintToChatAll)
- Fix for bug when client messages printed for all players

## 2.0.dev9
- Fix for AutoRespawn timer.
- Fix error when player disconnected and clientid is 0.
- Fix for not worked WinPoints.
- Fix for choosen immortality.
- Fix for players on choosen spawn in first round.
- Fix for not worked "self-destroyer showing as choosen kill self-destroyer".
- Add cvar for disable adding kills to choosen for suicide players.

## 2.0.dev8
- Changed code structure
- Fixed en lang
- Fixed 2 errors
- If player suicide - all see choosen killed them and all choosens get +kill.
- WinPoints now can work without SaveScores and work correctly with CS:S (in CS:GO winpoint - score, in CS:S - kills)

## 2.0.dev7
- Mixing players (dr_random 1) now work!

## 2.0.dev6
- Support for Counter-Strike Source

## 2.0.dev5
- Add variable for disable autorespawn hint (dr_autorespawn_hint)
- Fix little errors in main.cfg

## 2.0.dev4
- Fix problem with disconnected choosen

## 2.0.dev3
- Add support for 2 and more choosens with variable dr_random_rate

## 2.0.dev2
- Fix error in selecting choosen, when nothing players on the server

## 2.0.dev
- Team management
- Autorespawn
- Autoban disconnected choosens
- Save scores