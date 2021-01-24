# Java Chess AI Engine

This repository is a representation of a chess engine using pure Java. 

# Table of Contents

1. [Package com.chess.engine](#packageone)
2. [Package com.chess.gui](#packagetwo)
3. [Package com.chess.pgn](#packagethree)
4. [Games Database](#sql-games)
5. [Demo](#demo)


## Package com.chess.engine<a name="packageone" />

### Engine Contents

1. [Board](#board)
2. [Openings](#openings)
3. [Pieces](#pieces)
4. [Player](#player)
5. [Player-AI](#player-ai)

### Board <a name="board" />

The board is represented as a one-dimensional array of 64 elements. The 'a8' field is the first element, 'h1' field is the last element.
Board is represented as a group of tiles. Every tile is mapped to a given element in the array.

### Openings <a name="openings" />

Openings file in this package is designed to import exact positions into a database.

### Pieces <a name="pieces"/>

//Pieces Description//

### Player <a name="player" />

//Player Description//

### Player AI <a name="player-ai" />

//Player AI Description//

## Package com.chess.gui<a name="packagetwo" />

### GUI Contents

1. [Game History Panel](#ghpanel)
2. [Game Setup](#gsetup)
3. [Table](#table)
4. [Taken Pieces Panel](#tppanel)

### Game History Panel <a name="ghpanel" />

//Board Description//

### Game Setup <a name="gsetup" />

//Openings Description//

### Table <a name="table"/>

//Pieces Description//

### Taken Pieces Panel <a name="tppanel" />

//Player Description//

## Package com.chess.pgn<a name="packagethree" />

### PGN and FEN

1. [PGN](#PGN)
2. [FEN](#FEN)

### PGN <a name="PGN"/>

//Pieces Description//

### FEN <a name="FEN" />

//Player Description//

## Games Database<a name="sql-games" />

This SQL database contains 2.5 million chess games. All of them were scraped from https://pgnmentor.com.
Java code connects to a PostgreSQL database. Thus, commands in the source code are tailored for a local PostgreSQL database.
To run the code, install pgadmin4, create a database called "chess" and run the following file.

#### Note: The file is 1 GB

[Link]
⋮
[1]: https://drive.google.com/file/d/1vr0vLnZxNj7YCMhwCtdAd4ULZw4OSwQj/view

## Demo<a name="demo"/>

[Link]
⋮
[2]: https://drive.google.com/file/d/1vr0vLnZxNj7YCMhwCtdAd4ULZw4OSwQj/view
