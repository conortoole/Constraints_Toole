# 8 Queens
To run this program make sure the files are all in the same folder and navigate to 8Queens.py
Then click run without debugging and answer the questions in the terminal

## implementation
This code used a series of tile classes that contained their parent (previous) their children and their neighboring tiles. These neighbor tiles are stored as cardinal directions (N,S,E,W,NE,SE,SW,NW). This allows the program to quickly traverse in any direction similar to how the queen would move on a chess board. 

## Example output for c1:

select a starting position from row 1 (A1, B1 etc)c1

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2A
Row: 3G
Row: 4E
Row: 5H
Row: 6B
Row: 7D
Row: 8F


total number of backtracks before this solution was found: 
Forward Checking:  41
Directional Look Ahead:  25

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2E
Row: 3B
Row: 4H
Row: 5A
Row: 6G
Row: 7D
Row: 8F


total number of backtracks before this solution was found: 
Forward Checking:  27
Directional Look Ahead:  19

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2E
Row: 3B
Row: 4H
Row: 5F
Row: 6D
Row: 7G
Row: 8A


total number of backtracks before this solution was found:
Forward Checking:  4
Directional Look Ahead:  3

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2E
Row: 3G
Row: 4A
Row: 5D
Row: 6B
Row: 7H
Row: 8F


total number of backtracks before this solution was found:
Forward Checking:  5
Directional Look Ahead:  20

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2E
Row: 3H
Row: 4D
Row: 5A
Row: 6G
Row: 7B
Row: 8F


total number of backtracks before this solution was found:
Forward Checking:  30
Directional Look Ahead:  8

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2F
Row: 3B
Row: 4E
Row: 5H
Row: 6A
Row: 7G
Row: 8D


total number of backtracks before this solution was found:
Forward Checking:  10
Directional Look Ahead:  9

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2F
Row: 3B
Row: 4G
Row: 5A
Row: 6D
Row: 7H
Row: 8E


total number of backtracks before this solution was found:
Forward Checking:  6
Directional Look Ahead:  4

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2F
Row: 3B
Row: 4G
Row: 5E
Row: 6A
Row: 7H
Row: 8D


total number of backtracks before this solution was found:
Forward Checking:  3
Directional Look Ahead:  6

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2F
Row: 3D
Row: 4A
Row: 5H
Row: 6E
Row: 7G
Row: 8B


total number of backtracks before this solution was found:
Forward Checking:  7
Directional Look Ahead:  3

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2F
Row: 3D
Row: 4B
Row: 5H
Row: 6E
Row: 7G
Row: 8A


total number of backtracks before this solution was found:
Forward Checking:  5
Directional Look Ahead:  4

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2F
Row: 3H
Row: 4A
Row: 5D
Row: 6G
Row: 7E
Row: 8B


total number of backtracks before this solution was found:
Forward Checking:  8
Directional Look Ahead:  18

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2F
Row: 3H
Row: 4A
Row: 5E
Row: 6G
Row: 7B
Row: 8D


total number of backtracks before this solution was found:
Forward Checking:  3
Directional Look Ahead:  3

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2F
Row: 3H
Row: 4B
Row: 5D
Row: 6A
Row: 7G
Row: 8E


total number of backtracks before this solution was found:
Forward Checking:  4
Directional Look Ahead:  31

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2G
Row: 3B
Row: 4H
Row: 5E
Row: 6A
Row: 7D
Row: 8F


total number of backtracks before this solution was found:
Forward Checking:  27
Directional Look Ahead:  13

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2G
Row: 3B
Row: 4H
Row: 5F
Row: 6D
Row: 7A
Row: 8E


total number of backtracks before this solution was found:
Forward Checking:  4
Directional Look Ahead: no solution

Solution 1 with Queen 1 in Position 1C:

The positions of the Queens are:
Row: 1C
Row: 2H
Row: 3D
Row: 4G
Row: 5A
Row: 6F
Row: 7B
Row: 8E


total number of backtracks before this solution was found:
Forward Checking:  46
Directional Look Ahead: no solution
Total numbers of backtracks before this solution was found:
Forward Checking: 249
Directional Look Ahead: 166
