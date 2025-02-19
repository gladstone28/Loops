link to lesson:

https://www.codecademy.com/paths/code-foundations/tracks/learn-how-to-code/modules/bop-iii/lessons/bop-loops/exercises/for-loops


### Loops

**For Loops**

When we give instructions once and tell the computer how many times to repeat them, we are using a for loop, or a count-controlled loop. It executes a set of instructions for a specified number of times:

```
For 10 times:
  placeTile('pink')
  placeTile('orange')
  placeTile('mint')

```

The tile-placing instructions are the same from the previous exercise – Place a pink tile, Place a orange tile, Place a mint tile – written as calls to the placetile() function.

When a computer receives this program it sets a counter to 0 and executes the instructions in the body of the loop. After each iteration (one pass through the instructions), it advances the counter by 1. The process repeats until the counter is 10, meaning 10 iterations are completed.

The for loop is good to use when you know the number of times you’d like to perform a task before you begin, like printing 3 copies of a document or inserting 8 rows into a table.

