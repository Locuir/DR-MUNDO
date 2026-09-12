This repository contains my bots created for the Defector Prisoner's Dilemma competition.

This bot handles the dilemma by checking the opponent's status.

If the opponent is passive (choosing "C" 3 times), the bot will stay passive and choose "C".

If the opponent is aggressive (choosing "D" 3 times), the bot will become aggressive until they choose "C" 3 times.

The first time the opponent chooses "D", the bot will choose "D" and check their next move.

If they choose "D" again, the bot will enter adaptive mode, copying the opponent's moves.

If they choose "C", the bot will continue with the current state (passive or aggressive).

Here is the bot's page. [Check it out!](https://defector.hackclub.com/bot/gdfianaaqkvto5os8orb)
