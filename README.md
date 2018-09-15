# DomiUnos

Compile: javac *.java

BIG NOTE BEFORE YOU RUN:
If you want the graphics to display properly (which you 100% do), you must edit some code to do so to correctly.
1. Go to drawing.java. Look directly above the "KEY BINDINGS" section.
2. You should see:  Image background = Toolkit.getDefaultToolkit().createImage("C:\\\\Users\\\\juper\\\\Desktop\\\\background\\\\background1.jpg");
    Image waiting = Toolkit.getDefaultToolkit().createImage("C:\\\\Users\\\\juper\\\\Desktop\\\\background\\\\dominoesfall.gif");
3. In the zip file we submit, there will be background1.jpg and dominoesfall.gif saved in an "images" folder.
4. Wherever you choose to save the zip file, make sure you change the address that you pull the image from in the drawing.java code. For example, if you save it on your desktop, your address should probably read something like ("C:\\\Users\\\alfeld\\\Desktop\\\zipfolder\\\images");.
5. Do this for "Image background" and "Image waiting" in drawing.java & for 
        btnPlay.setIcon(new ImageIcon("C:\\Users\\juper\\Desktop\\background\\playbutton.jpg"));
        label.setIcon(new ImageIcon("C:\\Users\\juper\\Desktop\\background\\3D-Dominunos.jpg"));  
   in Window.java.
6. With these 4 addresses changed (in drawing.java & Window.java), the graphics should run properly!
Run: Window.java

Use:
DomiUnos Rules:
  1. 2 players (alternating turns)
  2. To start, each player is given 7 dominos
  3. Yellow dominos mean skip and green dominos indicate draw another tile
  4. If Player 1 sets down a yellow domino (if it fits), then Player 2's turn is skipped and Player 1 goes again
  5. If Player 1 sets down a green domino (if it fits), then Player 2 draws another tile from the shuffled pile (does this automatically)
  6. Player one goes first, playing any domino he/she wishes from his/her hand by clicking and dragging a domino to the center of the screen
  7. Each turn a player lays the dominoes end to end (the touching ends must match: i.e., one’s touch one’s, two’s touch two’s, etc.)
  8. Once a player's turn ends, a pop up that says "Next Player" will appear. The player who just set down their tile is to turn the computer towards the his or her opponent and let them press "OK". It is now the opponent's turn and the first player must wait for his/her opponent to finish their turn. The opponent turns the computer to the first player and the first player presses "OK". 
  9. A player can press the left or right buttons to shift the pieces in the middle of the screen to view the dominoes on the table
  10. The player is to click the desired domino and drag the tile to the area he or she wants to place the domino
  11. If a player cannot make another move with their tile, they must draw a domino until they can place one unless there are no more tiles to draw from. If the latter is true, then the other player places their tile.
  12. The round ends when either no more moves are left to make (all tiles used) or one of the players does not have any tiles left in his/her pile.
  13. Game ends when one player gets 100 points with as many rounds as needed. The points are tallied by the end of each round through the values on the leftover dominos in one's hand
  14. Whoever gets 100 points first loses
