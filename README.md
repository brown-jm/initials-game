# initials-game
Data, code, analysis, and results for the Initials Game from the Powertrip Morning Show on KFAN radio.

## The data
The data file, `initials.csv`, was manually created by me, using the history of games tracked on https://theinitialsgame.weebly.com/ Credit to the author of that site for tracking all the games!

Data updated as of Game 340 (5/28/2021).

### Variables in the data
Each row corresponds to one game of initials.
1. `week`: The index number for the given game. E.g., `1` corresponds to the first game. Note: For "Powertrip Majors" weeks where three games of initials were played in one show, the given `week` value is repeated three times.
2. `first`: The first initial for the given game.
3. `last`: The last initial for the given game.
4. `both`: The combined initials for the given game.


## Letter distributions
`letter-distributions.Rmd` contains the R-Markdown code used to process the data and produce the following two plots (updated as of 5/17/2021):

Percentage distribution of the letters used as the first initial.
![alt text](https://github.com/brown-jm/initials-game/blob/main/plots/first-letter-percentage.png?raw=true)



Percentage distribution of the letters used as the last initial.
![alt text](https://github.com/brown-jm/initials-game/blob/main/plots/last-letter-percentage.png?raw=true)

## One-letter Matching
`one-letter-match.Rmd` contains the R-Markdown code used to process the data and produce the plot below (updated as of 5/28/2021)

The plot shows the results from 5,000 simulations. In each simulation, the outcome is the number of games (or weeks) it takes to correctly guess the first or last initial. This was simulated by assuming both the caller and Cory Cove randomly choose their initials from a distribution of letters reflecting the historical percentage of use. Thus, the following plot is true to reality to the extent that the behaviors of the callers and Cory mimic this random draw.

![alt text](https://github.com/brown-jm/initials-game/blob/main/plots/sim-one-letter-match.png?raw=true)
