# Tic-Tac-Toe-Game
Tic-Tac-Toe-Game is a very simple game is a paper-and-pencil game for two players who take turns marking the spaces in a three-by-three grid with X or O.
The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row is the winner. It is a solved game, with a forced draw
assuming best play from both players.It is also called noughts and crosses in 'Commonwealth English, and Xs and Os in Irish English.

# Rules of the Game
->The game is to be played between two people (in this program between player1 and player2).
->One of the player chooses ‘O’ and the other ‘X’ to mark their respective cells.
->The game starts with one of the players and the game ends when one of the players has one whole row/ column/ diagonal filled with his/her respective character
(‘O’ or ‘X’).
->If no one wins, then the game is said to be draw.
![image](https://user-images.githubusercontent.com/91776867/174728065-2b574911-4b68-4e53-a501-a7034b98071a.png)


## Implementation
In this program ,I have coded mainly 2 function to perform the task required for this to execute.
Two functions are:  void board(); 
                    int checkwin();
                    
 **void board()**
 In this function ,I simply  created code to draw board for players with their marks.Mark of player1 will be 'X' and for playerr2, it will 'O'.
 Initially the board will be marked with number 1 to 9.
 void board();                  
                   
![image](https://user-images.githubusercontent.com/91776867/174722131-f5530b0f-0fc2-44de-bd1a-eefaad7f5dd0.png)

**int checkwin()**
This function will check game status if any of the player has win.
The function will return:
	1 FOR GAME IS OVER WITH RESULT
	-1 FOR GAME IS IN PROGRESS
	O GAME IS OVER AND NO RESULT
  
  **main() function**
  In main( function ,we will take input of player1 and player2 what number players want to take.Acoording to user input,It will mark on board 'X' for player1 and 'O'
  for Player2.After each user input,it will run checkwin() function ,to check whether any of player is winning.
  For example,Player1 entered input : 2.The board will appear like this.Since there is no winner it will proceed.
  
  
  
  ![image](https://user-images.githubusercontent.com/91776867/174727622-581afa26-7cd4-4f4c-8e30-b133a5343e24.png)

  
  
  Further,Player2 entered input:7,the board will look like this
  
  
  ![image](https://user-images.githubusercontent.com/91776867/174723817-bd1bcf42-5e6d-4374-b4ed-ce1f603deb67.png)
  
  
  
  Further,Player1 entered input:3,the board will look like this
  
  
  ![image](https://user-images.githubusercontent.com/91776867/174724033-a78127fc-7ce9-4968-ad97-50fa1c4a65ff.png)
  
  
  Further,Player2 entered input:5,the board will look like this
  
  
  ![image](https://user-images.githubusercontent.com/91776867/174724151-48575aee-5597-4427-b6c1-f1e47c1ccd9f.png)
   
   
   
   Further,Player1 entered input:1,player1 will win the board will look like this
   
   
   ![image](https://user-images.githubusercontent.com/91776867/174725117-6b1c2977-4237-4dae-8d32-f99fe07f230b.png)
   
