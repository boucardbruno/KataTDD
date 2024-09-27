Diamond Kata
============

Given a letter, print a diamond starting with ‘A’ with the supplied letter at the widest point.

For example: print-diamond ‘C’ prints

<pre><code>
  A
 B B
C   C
 B B
  A
</pre></code>

The usual approach is to start with a test for the simple case where the diamond consists of just a single ‘A':

<pre><code>
> PrintDiamond('A');

A
</pre></code>

The next test is usually for a proper diamond consisting of 'A’ and 'B':
<pre><code>
> PrintDiamond('B');

 A
B B
 A
</pre></code>
It’s easy enough to get this to pass by hardcoding the result. Then we move on to the letter ‘C':

<pre><code>
> PrintDiamond('C');

  A
 B B
C   C
 B B
  A
</pre></code>