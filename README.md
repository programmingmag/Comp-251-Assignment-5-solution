# Comp-251-Assignment-5-solution

Download Here: [Comp 251: Assignment 5 solution](https://jarviscodinghub.com/assignment/comp-251-assignment-5-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. (50 points) Fun with balloons
After a birthday party held in McIntyre 504, N balloons are left in the room, floating from left
to right. Bored TAs like to play with bows to practice their hunting abilities. During such a
practice, they position themselves at the left end of the room and shoot an arrow towards the
right end of the room from an arbitrary height they choose. Because Computer Science TAs
are not very good at physics, assume the arrows fly in a straight line at the height H chosen by
the shooter. When an arrow comes in contact with a balloon, the balloon disappears and the
arrow continues its way from left to right at a slightly lower height H-1, in a straight line. In
other words, if the arrow travelling at height H comes in contact with a balloon at position i,
then at position i+1, the arrow will be at height H-1, and will maintain that height until it hits
another balloon or the wall. Your task is to write a java class balloon.java that, given an
assignment of balloon positions, will compute the numbers of arrows necessary to destroy all
the balloons.
The input file is named testBalloons.txt. Line 1 contains an integer n that represents
the number of problems included in the file. Line 2 contains n integers mi separated by a
space, each representing the total number of balloons of the ith problem. Starting at line three,
every line describes a new problem. Each line contains mi
integers hj separated by a space,
which represent the respective height of the jth balloon from left to right.
The output file, named testBalloons_solution.txt, contains n lines, one per problem. Each line includes a single integer, representing the number of arrows that need to be
shot to destroy all the balloons of the corresponding input.
To summarize, the command java balloon should generate the output file. Same goes for
the other two exercises.
2. (50 points) Mancala Leapfrog
When TAs have nothing else to do, they like playing games. Because some of them do not have
many friends, they particularly like single-player games, like a specific variant of mancala,
played with small pebbles. In that game, the player is given a board with 12 cavities on a
single line. Some of them contain a pebble, and some don’t. The goal of the game is to remove
as many pebbles as possible from the board. Pebbles are removed through moves. A move
is possible when there is a straight line of three adjacent cavities A, B, C where A is empty
but both B and C contain a pebble. The move consists of moving the pebble from C to A, and
removing the pebble at B from the game. Such a move can be executed in both directions.
Unfortunately, some TAs struggle with the game, and they ask you to write a program to
help them. Your java class mancala.java should, given an assignment of pebbles over a
mancala board of size 12, find a sequence of moves such that as few pebbles as possible are
left on the board.
The input file, named testMancala.txt, has, like exercise 1, the number of included
problems as its first line. Other lines each contain a problem, represented as a sequence of 12
COMP 251 – HW5 Page 3 of 4 Fall 2018
integers. 0 represents an empty slot, and 1 encodes the presence of a pebble at that position.
The output file, named testMancala_solution.txt, contains n lines, one per problem.
Each line includes a single integer, representing the minimum number of remaining pieces at
the end of the optimal move sequence. For example, if the input position can be solved in such
a way that no pebbles are left after 4 moves, the output should be 0.
3. (50 points) Discovering islands in the ocean
Back in the 1830s, one of the first grad students at McGill University had the idea of using
satellites images to search the oceans for new islands to avoid very expensive exploration
voyages. Unfortunately, the resolution on satellite images was not stellar in those times, so the
bitmap images they produce require some post-processing. Your task is to help this visionary
grad student by writing a java class islands.java, which should be given as input an
image, more precisely a 2D array of black or white pixels, and output the number of islands
found in that image. Each pixel in such an image is either black (#) or white (-). Black pixels
are associated with water, and white pixels are parts of an island. All pixels that are adjacent
vertically or horizontally should be considered to be part of the same island.
The input file is named testIslands.txt. Line 1 contains an integer n that represents
the number of problems included in the file. The rest of the lines contain n input arrays of
pixels. Each input begins with a line containing a pair of integers 1 ≤ m, n ≤ 100. This line
is followed by m lines, each containing exactly n pixels.
The output file, named testIslands_solution.txt, contains n lines, one per problem.
Each line includes a single integer, representing the number of unique islands observed in the
corresponding input. Part of an island can still be counted as an observation of an island.
You will submit your three java files in a single zip file.

