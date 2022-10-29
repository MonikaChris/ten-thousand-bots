# Ten Thousand Game

# Attribution:
Thanks to Ryan Mckenna for his Farkle probabilities. These were used to determine when to bank or re-roll.
http://www.ryanhmckenna.com/2018/07/optimal-strategy-for-farkle-dice.html


## Version 1

- GameLogic class
  - roll_dice
  - calculate_score

- Banker
  - deposit/bank
  - shelf
  - clear

## Version 2

- beginning Game class
  - allows banking or quitting on first roll of multiple rounds
  - no rerolls
  - no zilches
  - no cheating checks
- Introducing Flow testing with Flo

## Version 3

- validate_keepers
- get_scorers
- Advanced Game class
  - rerolls allowed
  - using all six dice resets to six dice
  - zilches happen
  - cheating is checked

## Version 4

- Bot time
