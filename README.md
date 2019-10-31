# TF2: The Bee Movie Teamname Spammer
**The entire bee movie script, in teamname spam form.**

-------------
## Installation & Use
Download bee_spam.cfg, and place the file into your cfg folder.

In-game, open console and run `exec bee_spam`. 
During pre-game and post-game, press `=` to activate the script. 

To restart the script (back to the first line), open console and run `bee_reset`.

Do not run `exec bee_spam` multiple times, as it could cause multiple instances of the bee script running at the same time. However, do note that you could theoretically run ~10 instances, and cause each individual word to flood the entire chat one at a time.

-------------
## Information 
This script abuses the `tournament_teamname` that valve has left in the game. 
This command changes your team's name, and works in official casual servers. However, it has no effect to the game, and your team name is not displayed anywhere in-game during a match.
Running this command during a game or in the main menu will result in an `invalid command` response. 
However, during pre-game and post-game, this script will change the tournament name.
~~This command has no delay, and can theoretically be spammed thousands of times per second, which may be a possible method of crashing user. This was reported fixed by valve, however it may still result in slowdowns.~~ Valve has added a "feature" to kick players who spam commands too fast. This was added to stop users from crashing servers, but also limits this script's speed. Also, if you run left and right really really really fast, it can kick you from the game. Nice fix, valve.

**Pre-game** is defined as the first begining of a map, when players are still joining. You can recognize it by the 60 second countdown during the start of the game

**Post-game** is defined as the end of the map. You can recognize it by the map selection, and the scoreboard that displays over the entire screen.

-------------
## Warning
Using this script puts you at risk of being kicked from the server for cheating. Although this is not a cheat nor a hack, many people don't really know about the `tournament_teamname` command, and will assume that the spam is a cheat/hack. Attempting to tell them about the command will result in an `invalid command` on their part during the game. And, since `tournament_teamname` appears to be the only command in the game to have this behavior, chances are they'll assume you're lying and that it's a cheat/hack.

-------------
## Known bugs, issues, and limitations
Since this script only works during the pre-game and the post-game, chances are it won't really be useful. During the pre-game, there aren't that many players joining. Doing it at this time will result in not many people seeing it, and/or you have a risk of being kicked before even getting to play the game. During the post-game, the game has already ended and many players are likely to leave for a number of reasons. Doing it at this time will, again, result in not many people seeing it.

Some team names appear to not work properly for valve-reasons. For example, using the command `tournament_teamname "a"` will not change the team name to "a", but instead to "tourna". Why? No fuckin' clue. ¯\\\_(ツ)\_/¯
This is also the case for team names that have only two letters and begin with "t", and a few others.
Unfortunately, I am unable to tests these commands due to the limitations of the command only working in pre/post-game. I'll try, but do please report any errors.
