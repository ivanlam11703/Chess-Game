==============
=: Overview :=
==============

Chess game! I like chess and I like coding. Need I say more?


===================
=: Core Concepts :=
===================

1. Appropriately modeling state using 2-D arrays.
		I used a 8x8 array to model the chess board. 
		This is appropriate because a chess board is labeled by rows and columns.
		I can label positions of pieces with rows and columns on the board easily
		through a 8x8 2-D array (Although I probably should have figured out how to
		properly label the squares as on an actual chess board).

2. File I/O: using I/O to parse a novel file format.
		I used writers to write state of games to a text file in order
		to save it. I used readers to read the files and load a game state.

3. Using inheritance/subtyping for dynamic dispatch.
		I used an abstract class Piece and extended the different pieces from this
		class. This is appropriate because the different pieces share a lot of
		instance variables and methods. I chose abstract class over interface, 
		because the implementation of some methods is the same for all classes.
		
4. Complex game logic.
  		Chess has complex game logic. Each piece has a different way to move. There
  		are special situations like en passant, check, checkmate, and castling. It
		was a little tricky to implement this.
		
