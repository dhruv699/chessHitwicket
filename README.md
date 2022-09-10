# chessHitwicket

The Gamepiece class as two pure virtual functions: GetPiece() and AreSquaresLegal(). The function GetPiece() is overridden by each piece class to return the char that signifies each piece type: 'P' = pawn, 'N' = knight, 'R' = rook, 'B' = bishop. The function AreSquaresLegal() is overridden to test the source and destination locations versus the movement rules for the particular piece.

The board is numbered on the left and bottom from 1 to 5 so that locations ca be specified as a two-digit number and moves can specified as a pair of two-digit numbers. The green squares show the legal moves for a knight. So, that 43 to 31 is a legal move and will return true if passed into the knight's AreSquaresLegal() function.
