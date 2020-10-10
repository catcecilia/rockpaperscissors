This is for the [rock, paper, scissors assignment](https://www.theodinproject.com/courses/web-development-101/lessons/rock-paper-scissors)

Here is my psuedocode, I plan on doing the coding tomorrow:

define function computerPlay
let computerselection have a random value of either r,p,s
let playerslection have the user input value (either r,p,s)
converet playerselection to all lowercase
compare the values of computerplay and playselection
if computer wins, return a point to computer and a string stating You lose this round! computerselection beats playerselection
if player wins, return a point to player and a string stating You win this round! playerselectionbeats computerselection
else it is a tie, return a 0 point to player and a string stating Tie.

define function game
let countingpoints have the initial value of 0

let i be a counter from 0 to i< 5 that increments +1 with each pass
within counter, call function computerplay
subtract a point to countingpoints if computerplay returns a computer win
add a point to countingpoints if computerplay returns a player win
continue to next step if 0 points are returned

after i counter ends, compare computerpoint to 0
if countingpoints < 0 return a string stating that computer won the game
if countingpoints > 0 return a string stating that player won the game
if countingpoints = 0 return a string stating it is a tie

**_new pseudo code with dom manipulation_**
on load, start game function

for i = 0 and less than 5 ++:
add event listener to hear what div the user clicks
assign playerselection to the value of div clicked (r/p/s)
compare like previously to find if user won the round, lost the round or tied the round
inject result of round to html

after counter, check the player points
inject results to html
