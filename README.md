I've been getting alot of recommendations/suggestions for plugins. So I thought i'd keep the progress of them public for others to see.
Note: I work on these randomly (if at all) so if you are waiting for a plugin to use, understand the liklihood of it ever being finished is 1/100.

I work as a software engineer for a space company 40 hours a week, and am currently in the middle of getting my master's degree for software engineering. So any additonal coding I want to do usually goes into this stuff

Tombs of Amascut Point Tracker: Done
https://github.com/AbusiveTuna/ToA_Points

Thrall Utilities: I havent even started it

A general plugin to add some much needed QoL changes to thralls.
Remind you to bring book of the dead:
Hide thralls so you they stop hiding things under them:
^ Basically hiding thrall npc ids like you can do yourself, but in a checkable box.
Track thrall damage throughout fight:

Remove GIM: Like 10% done.
https://github.com/AbusiveTuna/remove-gim

Notes: Three ways to go about it.
1. Make a million highscore requests and check if the player in your general area is a gim.
2. We can have a locally saved list, that as soon as a gim chats (that we see), we can add that player to the list and hide them completely. 
3. Make our own highscore. Basically query the osrs highscores ourselves, find every single GIM, add them to a giant list, delete them (hide them).
  Two ways to go about #3.
    1. Have the list uploaded on plugin install, then add in functionallity from #2 to add new GIMs.
    2. Have the plugin query a website we create. The website would automatically query the highscores every day to find new GIMs.
    
This plugin is super complicated for such a dumb idea. Which makes me want to work on it more.
We could expand this to hide anyone at this rate. Hide normal accounts, hide all irons, etc.

