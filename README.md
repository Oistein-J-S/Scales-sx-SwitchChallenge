# About:
Mozilla Public License v 2.0 
https://www.mozilla.org/en-US/MPL/

This is quick reproduction of the Aon(cut-e) sx switchChallenge Deductive logical reasoning test.

Was unable to find reasonably priced test pacages so I did the computer enginner thing and made my own version.

# Functionality
sx switchChallenge is a 6-minute interactive assessment that measures logical reasoning. 
Each question has 4 symbols that change according to a number set. 
The task is to choose the set of numbers that reflects the symbols’ order at the bottom, in relation to the symbols at the top.

# Behaviour
Single level multivariable questions
        A, B, C, D
            |
2 3 1 4 | 4 2 1 3 | 2 4 3 1  
            |
        D, B, A, C

Multilevel single varriable questions
        A, B, C, D
            |
         2 4 3 1 
            |
2 1 4 3 | 1 3 4 2 | 3 4 2 1     
            |
        D, B, A, C

multilevel multivarriable questions. (1st layer only obfuscates the awnswer)
        A, B, C, D
            |
2 3 1 4 | 4 2 1 3 | 2 4 3 1  
            |
2 1 4 3 | 1 3 4 2 | 3 4 2 1     
            |
        D, B, A, C

# Usage
Open SwitchChallenge.html.
The test will start automatially.
Reload the page to take the test again.

# TODO
Some consept of difficulty level is missing (will just go through all possible questions regardless)
Some logic refraction would be nice to enhance code understandability
multilevel multivarriable questions need to generate it's own anwser sett.
    Both anwsers sets selectable?
Replace span ellement with CSS
Deny next if no awnser has been given? Or add a wrong anwser counter?