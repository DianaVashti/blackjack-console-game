# Team name: obsequious-mara, Members: DianaVashti
# goal #228 Goal Design and Build

This is a demo of goal #68:

## blackjack-console-game

## Notes for reviewer:
- The file for the goal design itself is called `GoalDescription.md` and is copied in this repo.
- To run this program:
  - Clone this repo and run `npm i` to install dependencies. Make sure the node version you are using supports es6 syntax (I am using node version 7.2.1)
  - `npm run test` will run the tests
  - `npm run start` will begin the game, the game will prompt you to type `y` between rounds if you wish to quit. Otherwise all commands and instructions will be provided by the game.


## Specifications

- [x] There is a README that includes directions for how to access, initialize, and run your game in the terminal/shell.
- [x] The file system is separated in to different files, and the separation is logical. (example: The code for how to shuffle a deck should live in a different place than the code for the logic in how the dealer behaves.)
- [x] Functions are concise and specific, and named in a way that is friendly to the reviewer / other learners.
- The end product is a playable blackjack game that satisfies the following sub-specs:
  - [x] The game is playable as one player and one dealer (AI)
  - [x] The player has a bank, and can continue playing rounds until they quit or are out of bankroll.
  - [x] The game tracks the bets, outcomes, and bank.
  - [x] The dealer/house has unlimited funds.
  - [x] The player can only see one of the dealers two cards during their turn.
  - [x] The dealer takes their actions after the user.
  - [x] The dealer gets to go second and will always try and win. (If you don't bust the dealer will hit until they win or bust.)
  - [x] An Ace is worth 11 unless it would put the player over 21, in which it becomes worth 1. This is still true for multiple Ace's (Example: A♠︎, A♣, 9♦︎ => 1, 11, 9 => 21)
  - [x] There is an exit command to terminate the game.
  - [x] The game does not allow you to bet more than you have.
  - [x] Each round begins by showing you your current bankroll, and you can bet as much or as little of that total as you wish.
  - [x] The house pays out on a 1:1 profit on wins (example: If you have $10, bet it all, and win, you now have $20)
  - [x] The game observes only the basic rules of blackjack: Natural blackjacks, ties lead to re-deals with the same bet, basic hit or stay abilities. Do not worry about more complex rules like doubling-down or splits.
  - [x] The artifact for the project is set and the readME includes the: Team name, goal number, team member handles, and a brief description of how to play your game (example: What is the command to quit, start, hit, or stay?)
