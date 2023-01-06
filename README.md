# game-bulls_and_cows
A past century game of guessing opponent's 3, 4 or 5 digit number

## Description
This game was written in 1999 and is placed here for memory of the good old days.
The game represents a Windows GUI application where a human and computer hide some digit number (3, 4 or 5 digits) and try to guess the opponent's number earlier than the opponent does. The game also runs in Linux with Wine installed.

## How to start
To start the game, simply unzip the Bulls3.zip file and run the extracted Bulls3.exe file. No installation is needed.

## How to play
The rules are shortly described in Help->"How to play" menu.
After clicking on 'New' button, the computer hides some N-digit number (where digits must not repeat) and immediately issues a number as the first attempt to guess the hidden number of the opponent.

The human should compare the issued number with his/her hidden number and first enter the number of cows (i.e. the number of existing digits but which are in different positions in the hidden number) and then the number of bulls (i.e. the number of existing digits which are in the same positions in the hidden number). 

After filling out those two fields, the program will open a larger edit box to let the human to enter a number as an attempt to guess the computer's hidden number. Once a number is entered the computer will immediately show the resulting numbers of cows and bulls from a comparison of the entered number with its hidden number.

The game lasts as long as one of the players guesses the hidden number (i.e. gets N number of bulls of N-digit number). The digit '0' is equivalent to other digits and may appear in the first position.
