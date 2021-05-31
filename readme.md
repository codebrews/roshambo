# Rock Paper Scissors
## Test your skills against the almighty ROSHAMBOBOT

### Works in console! (its a feature not a bug)

#### What it does:

-plays a game of best 3 out of 5 with the 'game()' function 
-also plays a single round with the 'playRound()' function
-player inputs via prompt
-computer randomly chooses paper, rock, or scissors via random interger value 0-2

Here is the psuedocode I wrote before scripting the project 
Get user input: rock paper or scissors 
make user input non case sensitive

Generate computer input: (random interger value 0-2)
    0 = rock
    1 = paper
    2 = scissors


round
    if UI = CI 
        tie, no score
        play again
    if UI = rock
        if CI = scissors 
            you win
            user score + 1
        if CI = paper
            you loose
            comp score + 1
    if UI = paper
        if CI = rock 
            you win
            user score + 1
        if CI = scissors
            you loose
            comp score + 1
    if UI = scissors
        if CI = paper 
            you win
            user score + 1
        if CI = rock
            you loose
            comp score + 1

Play full game (5 rounds)
    player score = 0
    computer score = 0
    play round
        add user score or computer score
        loop until either score = 3
    announce winner
