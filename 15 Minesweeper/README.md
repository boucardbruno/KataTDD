Minesweeper kata
================

Have you ever played Minesweeper? It’s a cute little game which comes within a certain Operating System whose name we can’t really remember. Well, the goal of the game is to find all the mines within an MxN field. To help you, the game shows a number in a square which tells you how many mines there are adjacent to that square. For instance, take the following 4x4 field with 2 mines (which are represented by an * character):
<pre><code>
* . . .
. . . .
. * . .
. . . .

</pre></code>

The same field including the hint numbers described above would look like this:

<pre><code>
* 1 0 0
2 2 1 0
1 * 1 0
1 1 1 0

</pre></code>

You should write a program that takes input as follows:
The input will consist of an arbitrary number of fields. The first line of each field contains two integers n and m (0 < n,m <= 100) which stands for the number of lines and columns of the field respectively. The next n lines contains exactly m characters and represent the field. Each safe square is represented by an “.” character (without the quotes) and each mine square is represented by an “*” character (also without the quotes). The first field line where n = m = 0 represents the end of input and should not be processed.

Your program should produce output as follows: 
For each field, you must print the following message in a line alone:
Field #x:
Where x stands for the number of the field (starting from 1).
The next n lines should contain the field with the “.” Characters replaced by the number of adjacent mines to that square.
There must be an empty line between field outputs.
This is the acceptance test input:

<pre><code>
4 4
* . . .
. . . .
. * . .
. . . .
3 5
* * . . .
. . . . .
. * . . .
0 0

and output:

Field #1:
* 1 0 0
2 2 1 0
1 * 1 0
1 1 1 0

Field #2:
* * 1 0 0
3 3 2 0 0
1 * 1 0 0

</pre></code>