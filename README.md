# chess
Each piece is a class
* Attributes
- color
- possible moves list
- current space
- moves graph

* Methods
- build_moves_graph()
- update current space
- destroy

ChessGame class to manage games
* Attributes
- board, 8x8 grid of pieces
- current color turn

* Methods
- check?
- checkmate?
- turn
- valid move?
- save game
- load game

module to convert space number to coordinates and vice versa