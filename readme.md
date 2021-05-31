# Rock Paper Scissors -- ##Test your skills against the almighty ROSHAMBOBOT

### Works in console! (its a feature not a bug)

This is my first JavaScript project. I completed it after spending some time studying JavaScript via The Odin Project. It plays individual and best 3 out of 5 rounds of Rock, Paper, Scissors with the computer in the console. No GUI for now. At the time this helped improve my skills with function, if statement, and loop syntax and especially with function and variable scope. 

Individual rounds are played with 'playRound()'  
Games of 3 out of 5 are played with 'Game()'

Here is the psuedocode I wrote before scripting the project:   
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
