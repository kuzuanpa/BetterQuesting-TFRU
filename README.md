 BetterQuesting-TFRU
============

Fork of GTNH BetterQuesting for the TFRU pack, original: https://github.com/GTNewHorizons/BetterQuesting.

## Notable local changes
- Removed the hard dependency on gtnhlib 0.7+.
- Added notifications for newly unlocked quests and switched quest notifications to localized quest names.
- Improved quest navigation by showing a dependency quest line when it differs from the current quest line.
- Replaced the open-inventory achievement to open-quest.
- Removed vending-machine-related code during local cleanup.
- When `taskLogic == OR`, ignored task(the Optional Receival) don't cause quests to complete.
- search widget limits search result counts to 64 to avoid lag.
