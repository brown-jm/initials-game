# initials-game
Data, code, and analysis for the Initials Game from the Powertrip Morning Show on KFAN radio.

## The data
The data file, `initials.csv`, was manually created by me, using the history of games tracked on https://theinitialsgame.weebly.com/ Credit to the author of that site for tracking all the games!

Data updated as of Game 352 (4/09/2021).

### Variables in the data
Each row corresponds to one game of initials.
1. `week`: The index number for the given game. E.g., `1` corresponds to the first game. Note: For "Powertrip Majors" weeks where three games of initials were played in one show, the given `week` value is repeated three times.
2. `first`: The first initial for the given game.
3. `last`: The last initial for the given game.
4. `both`: The combined initials for the given game.


## Letter distributions
`letter-distributions.Rmd` contains the R-Markdown code used to process the data and produce the following two plots:

Percentage distribution of the letters used as the first initial.
![alt text](https://github.com/brown-jm/initials-game/blob/main/plots/first-letter-percentage.png?raw=true)



Percentage distribution of the letters used as the last initial.
