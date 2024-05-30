/* Name: Group 6
 Member Huỳnh Minh Duy ITCSIU21174
        Nguyễn Nguyên Bảo Phú ITCSIU21216
        Nguyễn Trần Gia Huy ITITIU21054
 Purpose: Battleship game files explained. 
*/

README

The game Battleship

The game contains one player and one computer bot to execute,
The files are associated with one another.
The game runs on Javascript with many objects and functions.

The ship class generates the length of each ship using ArrayList.
    the ships are made of square which is defined by width*width which is the pixel on the game interface.

The createBoard class generates boards of two players which also has its board made of square.

The function generate is used for generating ships at different locations on the computer's board.

The function rotate is used for rotating the ship horizontally to vertically.

To move the ship onto the player's board there is the drag(Start, Over, Enter, Leave, End) function using the object draggedShipLength and draggedShip.

The dragDrop function is capable of checking the valid point to place the ship or not.

The playGameSingle helps the player to generate all the above and uses algorithms for the player to execute the game.

The revealSquare reveals each square if it is boom or miss and counts down the ships.

The enemyGo function is the algorithm for the bot to enter its movements.

The checkForWins notify if the ships are taken down and if the player or computer win the game.




style.css is the file that contains all the animation the game has.
If clicking on the Rungame file, the game should automatically start and open a web browser to generate the game.