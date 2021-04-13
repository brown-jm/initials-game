# initials-game
Data, code, and analysis for the Initials Game from the Powertrip Morning Show on KFAN radio.

Data updated as of Game 352 (4/9/2021).

## The data
The data file, `initials.csv`, was manually created by me, using the history of games tracked on https://theinitialsgame.weebly.com/ Credit to the author of that site for tracking all the games!

### Variables in the data
Each row corresponds to one game of initials.
1. `week`: The index number for the given game. E.g., `1` corresponds to the first game. Note: For "Powertrip Majors" weeks where three games of initials were played in one show, the given `week` value was repeated three times.
2. `first`: The first initial for the given game.
3. `last`: The last initial for the given game.
4. `both`: The combined initials for the given game.
