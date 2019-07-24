# sports-league
Prolog script that designs a league with N teams, with N-1 rounds (playing days), where every two teams play against each other on exactly one round, one team at home and the other team away, and on each round each team has exactly one match (home or away).

Moreover, we say that a team has a "double" on round R if it plays at home on rounds R-1 and on round R, or if it plays away on R-1 and on R.

The main objective of this script is minimize the number of doubles of the team with the largest number of doubles.

## How to execute
```
swipl
```
```
?- [basket].
?- main.
```
