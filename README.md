## Overview

This bot is made for the [Defector Program](https://defector.hackclub.com/) to be used in the Prisoner's Dilemma to try to get the biggest mean score and lead the leaderboard.

## How the Bot Works

The bot is made to counter different types of bots by analyzing the opponent's behavior and classifying them as passive, adaptive, or aggressive.

## Defence System

To counter them, we have some methods:

* If the bot chooses C 3 times in a row, we classify it as a passive bot, so we continue choosing C.
* If the bot chooses D 3 times in a row, we classify it as an aggressive bot, so we switch to D.
* If the bot's D rate goes above 40% after the 5th round, we classify it as an aggressive bot, so we switch to D.
* If the bot chooses D, we test its reaction by choosing D.
* If the bot chooses D again after our test, we classify it as an adaptive bot, so we start copying its moves.

## Offense System

* If the bot is classified as adaptive, we copy its previous move to respond to its behavior.

## Performance

Tested in a 2877 battle

Average Score: 9.062

Win Rate: 7.6%

Wins : 219

loses : 993

ties : 1,665

reached #1 on the leaderboard

Check how our bot performance here : [DR MUNDO](https://defector.hackclub.com/bot/mlj93z0t3mpmo1rafub6)

## Screanshots

<img width="1212" height="588" alt="Screenshot_13" src="https://github.com/user-attachments/assets/50cfb770-f67f-44c5-ad34-1a392bca09eb" />
<img width="897" height="441" alt="Screenshot_14" src="https://github.com/user-attachments/assets/8457f085-b3d4-4fb8-a524-b2abb762e776" />
