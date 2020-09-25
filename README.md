Rock Paper Scissors
Test your skills against the almighty ROSHAMBOBOT

Works in console! 

A few notes and fixes:
1) Most important issue to overcome was trying to return values prior to completing functions. Just set a variable which can be returned later
2) Played around with returning scores in the playRound function which would have worked
1) Put variable for score outside of functions global, which allowed this to be used between functions.

Psuedocode:
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
