 <h1 align=center>Battleship</h1> 

 Battleship is a python based game which, is displayed in the Code institute mock terminal on Heroku

 The aim of the game is for the user to find and sink all of the computers battleships before you run out of turns. Each Battleship occupies a single space on the board. 

 [view my project here](https://marks-battleship-game.herokuapp.com/)

 <h2><img src='images/am_i_responsive_img.png'>

# How to play

This game is based on the original pencil and paper game Battleship. You can find more information about it on [wikipedia](https://en.wikipedia.org/wiki/Battleship_(game))

my version of the game, 5 ships are randomly placed on the board.

the user has a total of 10 trys to successfully sink the computers battelships.

A single board is generated on the terminal, the user cannot see where the ships are placed.

ships are marked by the 'x' sign but, the user won't be able to see them until he guesses right.

previous guessess are marked with the '-' sign.

If the user is unsuccessful the terminal will state that you 'missed' and inform you how many turns you have left.

if you run out of turns before finding all the computers ships, the game ends.

# Features 

- ## Existing Features
    - The computer's ships are randomly placed on the board
    - The user cannot see the computer's ships
    - Numbers are used for rows 
    - and letters for columns so there is no confusion

<h2><img src='images/terminal-0-img.png'>

- ##### Play against the computer
- ##### Accepts row and column input 
- ##### Keeps score of how many turns left

<h2><img src='images/terminal-1-img.png'>

- ##### You can't choose a number or letter beyond the board grid
- ##### You must pick a number for rows 
- ##### And a letter for colmuns

<h2><img src='images/row-error-img.png'>
<h2><img src='images/column-error-img.png'>

- ##### You can't input the same guess twice

<h2><img src='images/guess-twice-img.png'>

# Data Model 

I used the GameBoard class as my model. this class creates a single game board while the Battleship class creates the battleships and randomly places them on the board.

The GameBoard class stores the size of the board as well as converts the columns letter inputs to numbers.

The Battleship class stores the data for the random ships to be placed on the board. It also has methods to allow the user to interact and input their choices. It further helps the user to play by keeping the score letting you know if you hit or missed and how many turns you have left.


# Testing 
### I have manually tested the code with the following:
- I have passed the code through PEP8 linter and confirmed there are no issues.
- Tested on in gitpod terminal and Code institute mock terminal on Heroku
- I have given invalid inputs. I have put numbers when I should input a letter, out of bounds and have put in the same input.

##  Bugs

 ### Solved Bugs

- when writing the code for the project I was getting the error 'e501'. I solved It by indenting the code after the opening Parentheses.

## Remaining Bugs

-  One of the 'E501' errors remain. I currently have not figured out a way to indent this line of code without generating a syntax error. So far any attempt stops the whole game from working.

<h2><img src='images/error-e501-img.png'>

# Deployment

This project was deployed using Code Institute's mock terminal on Heroku.

- How to deploy:
    - Click 'create new app' in Heroku
    - Set choose buildbacks python and NodeJS in that order
    - Choose GitHub as your deployment method then click connect
    - Link your repository to Heroku by inputing your reopository name
    - Click on Deploy


# Credits

- Credit goes to 'gbrough' over on github for providing the code. link can be found [here](https://github.com/gbrough/battleship/blob/main/single_player_OO.py)
- Code Institute for the deployment terminal
