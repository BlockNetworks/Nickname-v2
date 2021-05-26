# Nickname
Allows setting of Nicknames in PocketMine-MP!

This is a continuation of **[KadTheHunger/Nickname](https://github.com/KadTheHunter/Nickname)**.

# Requirements
- PocketMine-MP
- PureChat

# Usage
- Download the compiled `.phar` from Poggit
- Upload it to your servers `plugins` folder
- Go in-game, and use `/nick set <your nickname here>`
- For other Commands read below, or use `/nick help`

# Commands
- `/nick help` | Shows the list of Nickname commands 
- `/nick set <nickname>` | Sets your nickname 
- `/nick set <nickname> <player>` | Allows an Admin to set a players nickname
- `/nick reset` | Resets your nickname to your normal name
- `/nick reset <player>` | Allows an Admin to reset a players nickname
- `/nick see <player nick> OR <player name>` | Allows you to see who has a nickname, or what someones nickname is.

# Whats Different
Please note that Kad didn't actually write most of this Plugin, he simply found it, fixed it, and upgraded it. The original creator of it has long since dissapeared, and the 1st editor of it, ElektroPrinz, has deleted his repository of it. The changes listed below are in chronological order of when Kad fixed them.
 
- Fixed the Namespace {[9272787](https://github.com/KadTheHunter/Nickname/commit/927278741b5dccf4862690ed465aca09a9132f04)}
- Fixed typos in the messages {[269203a](https://github.com/KadTheHunter/Nickname/commit/269203acf25be73c905359c9741d49311af3eec7)}
- Added temporary support for Nametags (you cannot change how they look currently, maybe in a future update) {[6eadddc](https://github.com/KadTheHunter/Nickname/commit/6eadddc250d4e03c990548b82e216de04d5d46a8)}
- Fixed an issue where when an Admin used `/nick set <nick> <player>` and `keep-nick` was set to `true`, the nickname was incorrectly saved under the Admins username. {[83ab871
](https://github.com/KadTheHunter/Nickname/commit/83ab871f0a999cf03eb16b553ecc2271a4449968)}
- Added proper support for nametags as of July 20th, 2020. {[2a9400e](https://github.com/KadTheHunter/Nickname/commit/2a9400e4f5b19a5948ea2ad79696371d2687a7b8)} {[5dc6c1f](https://github.com/KadTheHunter/Nickname/commit/5dc6c1fbcb5aa7626022b42c01d3f3b164e35684)} {[94a2ae3](https://github.com/KadTheHunter/Nickname/commit/94a2ae310a0a0c5f6dbabcafc5ca2af301e0d187)}
