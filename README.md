# Rock, Paper, Scissors game

A CLI application that allows the user to play rock, paper, scissors against the computer.
I  wrote the rules of the games into a CSV which displays at start of game
The user chooses best of 3 or 5 games
The score is kept when necessary wins is met a winner is chosen
Score is written to MongoDB
User can choose to play again or quit
Once user chooses quit the collection is deleted.


# Tech Stack
Python3 
pymongo, random, mongo client

MongoDB
Windows Powershell
VS Code
Git/GitHub

# Features
	

- Best of 3 or 5 games 	
- Calculates winner by adding score of games won
- Raise an error if user doesn't input rock, paper, or scissors or misspells the words
-  Raise an error if user doesn't input anything or hits enter by mistake

**To-do list**
- Implement update feature to change user score
- Implement a way to quit game and keep saved data in MongoDB

# Getting Started
Download VS Code
Download Python extension
Download MongoDB
Download Pymongo extension

![enter image description here](https://ucarecdn.com/067526a7-03d1-441b-8ea1-85aaca48638d/visualstudiodownload.png)



# Usage

- Below is a screenshot of the game being played, it displays how many games the user wants to play
- Displays the user misspelling scissors and gives an error message
- Displays the users choice and if he/she won 
- Displays overall winner and points scored

![enter image description here](https://ucarecdn.com/8431b3c8-00f9-471c-a501-426d2049ca86/ScreenshotOfgame_played.png)






