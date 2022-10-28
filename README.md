# JS-mini-project-1305

Game Title: TIC-TAC-TOE

Live on: https://incredible-bunny-34aff0.netlify.app

Overview:
The tic-tac-toe game is for two players. One player plays X and the other plays O. The players take turns placing their marks on a grid of three-by-three cells. If a given player gets three marks in a row horizontally, vertically, or diagonally, then that player wins the game.

Rules of the Game:
1. The game is to be played between two people (in this program between HUMAN and COMPUTER).
2. One of the player chooses ‘O’ and the other ‘X’ to mark their respective cells.
3. The game starts with one of the players and the game ends when one of the players has one whole row/ column/ diagonal filled with his/her respective character (‘O’ or ‘X’).
4. If no one wins, then the game is said to be draw.

Winning Strategy – An Interesting Fact:
If both the players play optimally then it is destined that you will never lose (“although the match can still be drawn”). It doesn’t matter whether you play first or second .In another ways – “ Two expert players will always draw ”.

Games can showcase our skills in a very good manner. Hence, I have chosen this game to show my skills. 

In the HTML part of the code, I have assigned id tags and classes to the elements of the board. JavaScript will take care of all the interactions in the game. Lastly, the CSS stylesheet will personalize the visual appearance of our game. 

In the body I created my board and named its class and id. I also assigned the “tile” class to the cells inside the board. I added a few more <div> elements for my winning message and the restart button.

I created a constant variable for our x and o characters. The table under presents combinations of movements for winning the game. These combinations will help to determine if the game is over or not, by checking if any of the combinations match the current gameplay.
