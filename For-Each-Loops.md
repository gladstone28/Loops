link to lesson:

https://www.codecademy.com/paths/code-foundations/tracks/learn-how-to-code/modules/bop-iii/lessons/bop-loops/exercises/for-each-loops


Loops
For Each Loops
3 min
There’s one more way to give looping instructions to a computer. We define a sequence of desired tile colors (a list), and tell the computer to repeat the instructions for each item in the sequence. Here’s an example list:

```
festiveList = ['pink', 'green', 'red', 'pink', 'green', 'red' ]

```

and the loop would look like:

```
For each color in festiveList:
  placeTile(color)

```
Why does this program look shorter than the ones before it? We only need to write placeTile() once because the pink-green-red repetition is already described in the list.

color is a variable whose value changes each iteration. It represents each item in the list. On the first iteration, its value would be 'pink', then 'green', then 'red', and so on.

The sequence we used was a list, but we can use other similar 
Preview: Docs Loading link description
data types
. The umbrella term for those is collection, so we may also call for each loops collection loops.

Use this loop when you need to perform a task for every item in a list, or when the order of things must be maintained. In this case, both were important. A tile must be placed for each item in the list and the order of them is essential to the pattern.
