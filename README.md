# Queen-s_Gambit_Challenge
Data for 20,000+ chess games played on Lichess

### About the dataset

    We’re looking at over 20,000 online chess games played on Lichess
    Each record represents one game
    Records contain details about the winner, player ratings, moves, and more!

### Working with chess data

Before you jump in, there may be few things you need to know about chess to read the “moves” field in the dataset...

Chess is played on an 8x8 board between two players, white and black, where white always has the first move.

Chess moves are recorded using algebraic chess notation, which specifies which piece moves to which square on the board.

The numbering and lettering of the chess board is oriented to the white player’s position and looks like this:

![Image](https://images.ctfassets.net/p80c52b4itd3/2Sc1a2h5BezSIZVk6lLvIl/5f89ebb5a0ae040aa38b060cfe4a067c/chess_board.png)

Chess Notation

Like each square for the chessboard, each chess piece also has a specific notation:

    King: K
    Queen: Q
    Bishop: B
    Knight: N (K is already taken)
    Rook: R
    Pawn: No notation (if a move indicates only a square, it's a pawn)

Below you can see the first 4 moves of the Ruy Lopez opening (e4 e5 Nf3 Nc6):

Chess Move 1 & 2

![Image](https://images.ctfassets.net/p80c52b4itd3/5SnRRH1rfw8fFwloCah8hK/f49f12182407b8f961bdbe50b44e5ebe/chess_move_1.png)

Chess Moves 3 and 4

![Image](https://images.ctfassets.net/p80c52b4itd3/3ihoeqizGL9WctqNcmLykM/6c8f2461abc2c3a335e8dc59eb836ffe/chess_move_2.png)

First, white moves a pawn to e4, followed by black to e5. For the second set of moves, white moves a knight to f3, black moves theirs to c6, and so on and so forth...

#### Recommended Analysis

    What percentage of games were won by white? How many ended in a draw?

    Which opening move was most frequently used in games in which black won? What about when white won?

    What percentage of games are won by the player with the higher rating? Does this vary by piece color?

    Which user won the most amount of games? In what percentage of those games was the user the higher rated player?
    
#### Bonus

Suppose YOU are playing black against Elizabeth Harmon, and she opened with the Queen’s Gambit (d4 d5 c4). What's your next move, and why?

She may be the best there is, but you have an ace up your sleeve; a rich dataset of online chess games to help prepare...
