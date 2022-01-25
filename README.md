# Project_TicTackToe
This is a game named TikTacToe developed using Java. 


TIC-TAC-TOE

Introduction:

In this oop project , we worked on a small game called tic-tac-toe .Tic-tac-toe is played on a three-by-three grid by two players, who alternately place the marks X and O in one of the nine spaces in the grid.There is no universally-agreed rule as to who plays first however,  tic-tac-toe is often played by young children who may not have discovered the optimal strategy. Here below we shall discuss the code flow and explain how our game operates. 

Project overview and manual:

The tic tac toe consists of a stand 3x3, row and column, the game starts as soon as  one person clicks a  button  in the grid. If the player has two in a row, they can place a third to get three in a row or column or diagonal,that player will win the game.This game requires some use of strategy, If the opponent has two in a row or column or diagonal the player must play the third themselves to block the opponent. The game can be generalized as two players alternate placing x or 0 of their own color on a 2d board with the goal of getting the same symbol on the same rows. 

Code Documentation:

The interesting java project will be built using the AWT and Swings libraries. We will be explaining all the steps as well as methods that are used in this project. Swings is a popular java library that is used to develop beautiful GUI applications.We used an IDE named NetBeans 8.2.
We declared a main class named “Main” and created an object of the “TicTacToe” class named “tictactoe”. “TicTacToe” class has implemented an “ActionListener” interface which has a method called “actionPerformed”. For making a window , we created an objects of “Frame” , “Panel”, “Button” classes.After which  we added some functionality of our window by creating a constructor , such as : giving it a fixed size , creating 9 buttons , keeping those button in panels and give a title and a label  to the panel ,and then add color to distinguish them between two players.Furthermore , we had to make the buttons visible and gave a grid layout to the buttons. In the actionPerformed method . As soon as  one player has clicked a button , his turn will end and his turn wll signify with a text color . After the player pressed one button and after which the “check” method will be called .The check method will check x condition and will check all possible options to win . X will only be able to win if the required options meet .If player one turn is over the text will be set as O and the player two turns will begin and it will work the same way as the player one  and at the end it will rewrite the settext as X . when checking the x options that  if x wins or not  it will check all the options within the if-else condition . If one player hits 3 buttons and the  condition meets , it will call upon a method called xwin() or owin() with a given set of parameters . Once a player wins the method will fetch parameters for the button that will turn them green and after which “thebuttons[i].setEnabled(false)” will become false  and it will show a “text that the player wins”.
There is a method “firstTurn()” inside the constructor which controls the exception and helps to handle the “interrupt exception”. First turn player will be denoted by x turn and the second player will be denoted by o turn,between each time the program will sleep for 2000 millisecond.


Conclusion: 

We have successfully developed a simple tic tac toe game in java. The Tic Tac Toe game is most familiar among all the age groups.Intelligence can be a property of purpose-driven decision makers.  Overall the system works without any bugs.It is easy to play between two players.It is straightforward to write a computer program to play tic-tac-toe perfectly or to enumerate the 765 essentially different positions  or the 26,830 possible games up to rotations and reflections in this space.This basic idea has been suggested many times. An algorithm of playing Tic Tac Toe has been presented and tested that works in an efficient way. The program will show which player wins while the button that was clicked will turn green . If the players want to play the game again they can rerun the program for a second time.

