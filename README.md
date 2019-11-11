# Mastermind
A console mastermind game in C#


I developed this game as coursework in the first year of university. The aim was to develop an understanding algorithms by creating 
mastermind as a console application.

Objective:

The aim of the game is to correctly guess the digits in the secret hidden code that is randomly generated. You get to pick the maximum 
value of the digits in the code as well as the length of the code.

White/Black pieces:

After you make a guess, the game will show you how many black and white pieces you received for your guess.
White pieces represent a correct value in the wrong position within the code.
A black piece represents a correct value in the correct position.

EXAMPLE:

Secret Code: 1234

If you guessed 4321 you would get White Pieces: 4 Black Piece: 0, as all for values are correct but none of them are in the right place.
A guess of 2214 would equal White Pieces: 1 Black Pieces 2, as 2 & 4 are in the right place however whilst 1 is the correct value, it is 
in the wrong position.

Thankyou and enjoy the game.
