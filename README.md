# Artificial-Intelligence_Project-1.0_Gomoku
Artificial Intelligence
Project 1
Due Date: 9th Week(Lab)
Overview
This project consists of developing and implementing a computer program that can play a game against a human opponent. The groups in the class are divided into two sections: even group will implement the game of Gomoku, and the odd will implement the game of Connect Four. The project will exemplify the minimax algorithm with alpha-beta pruning, and designing good evaluation functions.
Game description: Gomoku
Gomoku, also known as "five in a row", is a board game similar to tic-tac-toe but on a larger board. It is a two-player, fully observable, deterministic, zero-sum game. Players take turn in placing ‘stone’s in the board until one player can connect five stones of the same color in a row horizontally, vertically or diagonally. It is typically played in a 15 X 15 board, but for this project a 10 X 10 board is sufficient. Detailed information about the game can be found in: https://en.wikipedia.org/wiki/Gomoku
Game description: Four Connect
Four Connect is also a two-player, fully observable, deterministic, zero-sum game. Players take turn in dropping discs from the top of an upright board until one player can connect four discs of the same color in a row horizontally, vertically or diagonally. It is typically played in a 7 X 6 board (7 columns wide, 6 rows high). Detailed information about the game can be found in: https://en.wikipedia.org/wiki/Connect_Four
Project Requirements
- Your AI program must be able to play a reasonable game against a human or AI opponent.
- The program must have the following components.
o Searching the game tree using a suitable search algorithm
o Running minimax algorithm on the game tree to select the right move
o Implementation of alpha-beta pruning to make search faster
o Design and implementation of an effective evaluation function to evaluate the goodness of any intermediate node (state of the board).
o An early stopping mechanism to be able to abort search and return the minimax values based on the evaluation function.
- A functional user interface is expected. An aesthetic/graphical user interface is encouraged, and will bear extra credits.
Grades distribution
Game tree search + Minimax
30%
Alpha-Beta pruning
20%
Design and implementation of Evaluation function
20%
Early stopping of search
10%
Playing “reasonably well”
10%
Interacting well with user + UI
10%
There will be a mid-project evaluation where 33% of the marks of the project will be assigned. The remaining 67% will be assigned on the final project evaluation.
Deadline
The Midterm evaluation will be conducted on the 7th week. The final evaluation will be conducted on the 9th week. No submissions after the deadline will be accepted. Absolutely no exceptions will be made.
Academic Integrity Policy
The code of the project must be your own. Any libraries or code snippets that you use from other sources must me mentioned explicitly. Any kind of academic dishonesty will result in you getting a zero for this project, and possibly further repercussions.
