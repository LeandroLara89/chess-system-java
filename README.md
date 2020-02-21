# chess-system-java (Sistema de Jogo de Xadrez)

Objetivo Geral
  Aplicar os conhecimentos aprendidos até o momento no curso para a construção de um projeto
  
 # Starting to implement Board and Piece
 
## Checklist:
  - Classes Piece, Board [public]
  - OOP Topics:
- [x] Associations
- [x] Encapsulation / Access Modifiers
- Data Structures Topics:
- [x] Matrix

# Chess layer and printing the board

|

<p>8 - - - - - - - -</P>
<p>7 - - - - - - - -</P>
<p>6 - - - - - - - -</P>
<p>5 - - - - - - - -</P>
<p>4 - - - - - - - -</P>
<p>3 - - - - - - - -</P>
<p>2 - - - - - - - -</P>
<p>1 - - - - - - - -</P>
      a b c d e f g h
 
 ## Checklist:
- Methods: Board.Piece(row, column) and Board.Piece(position)
- Enum Chess.Color
- Class Chess.ChessPiece [public]
- Class Chess.ChessMatch [public]
- Class ChessConsole.UI
- OOP Topics:
- [x] Enumerations
- [x] Encapsulation / Access Modifiers
- [x] Inheritance
- [x] Downcasting
- [x] Static members
- [x] Layers pattern
- Data Structures Topics:
- [x] Matrix
 
# Placing pieces on the board
## Checklist:
- Method: Board.PlacePiece(piece, position)
- Classes: Rook, King [public]
- Method: ChessMatch.InitialSetup
- OOP Topics:
- [x] Inheritance
- [x] Overriding
- [x] Polymorphism (ToString)

# BoardException and defensive programming
## Checklist:
- Class BoardException [public]
- Methods: Board.PositionExists, Board.ThereIsAPiece
- Implement defensive programming in Board methods
- OOP Topics:
- [x] Exceptions
- [x] Constructors (a string must be informed to the exception)

# ChessException and ChessPosition
## Checklist:
- Class ChessException [public]
- Class ChessPosition [public]
- Refactor ChessMatch.InitialSetup
- OOP Topics:
- [x] Exceptions
- [x] Encapsulation
- [x] Constructors (a string must be informed to the exception)
- [x] Overriding
- [x] Static members
- [x] Layers pattern

# Little improvement in board printing
## Color in terminal:
- Windows: Git Bash
- Mac: Google "osx terminal color"
## Checklist:
- Place more pieces on the board
- Distinguish piece colors in UI.PrintPiece method
## Moving pieces
## Checklist:
- Method Board.RemovePiece
- Method UI.ReadChessPosition
- Method ChessMatch.PerformChessMove
- [x] Method ChessMatch.MakeMove
- [x] Method ChessMatch.ValidadeSourcePosition
- Write basic logic on Program.cs
- OOP Topics:
- [x] Exceptions
- [x] Encapsulation
