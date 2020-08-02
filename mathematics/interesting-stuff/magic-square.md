# Magic Squares

A magic square is a square grid with numbers in it (think sudoku). These numbers follow a certain pattern. Let's start of with a certain number, n.  

Let's define n as the sum of all the numbers in the first row. We quickly discover that the sum of all the numbers in the second, third, and fourth (and so on) rows is equals to n. Not only that, the sum of all the numbers in each column is also n. We call n the magic number of a magic cube. 

In some magic squares, the numbers in the four corner squares also sum to n and so do the four innermost squares in the centre of the square.  

| 16 | 2  | 3  | 13 |
|----|----|----|----|
| 5  | 11 | 10 | 8  |
| 9  | 7  | 6  | 12 |
| 4  | 14 | 15 | 1  |

Mathematics aside, magic squares have been thought by some to be objects of great power. There is a rich history of magic squares used across different cultures spanning from ancient India to China to Arabia and Rome. Although rational people nowadays don't believe that magic squares have anything to do with the divine or paranormal, magic squares still have some ethereal and elegant properties.

One interesting thing you can do with magic squares is magic tricks. I got this trick from David Blaine's (yes, that David Blaine) book, Mysterious Stranger. The trick purports a magician to be able to construct a magic square with any given number in order to impress the spectators with their massive intellect. I've described the trick as follows:

First, we must learn to construct a simple magic square. Start off with an empty 4x4 grid. Start filling up the grid in order from one to sixteen, but skip numbers that fall on the diagonals. If done correctly, your square would look like this:

|   | 2  | 3  |    |
|---|----|----|----|
| 5 |    |    | 8  |
| 9 |    |    | 12 |
|   | 14 | 15 |    |

With the numbers you've omitted, start filling the remaining squares but in descending order. So, start with 16, followed by 13, followed by 11, and so on. 

| 16 | 2  | 3  | 13 |
|----|----|----|----|
| 5  | 11 | 10 | 8  |
| 9  | 7  | 6  | 12 |
| 4  | 14 | 15 | 1  |

And you're done. There's your magic square with n = 34.

There's a simple formula to find an n for a square of any size. Take the number of rows, cube it, add the cube to itself, and divide it by two. The result you obtain will always be a magic number for the square. Before we do any magic, we'll need to learn another trick.

