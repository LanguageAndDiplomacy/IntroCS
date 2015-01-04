#Project 4: Bubble Sort
The purpose of this project is to implement an algorithm by yourself. You will be coding the bubble sort algorithm, which is a classic computer science algorithm for sorting lists. Along the way, you will practice using lists and building your own blocks.

The bubble sort algorithm is as follows:

1. Loop over the items in the list.
1. Compare each item with the item to its right.
1. If the two items are in the wrong order, swap them.
1. Repeat steps 1-3 until you loop over the entire list without doing any swaps.

![bubble sort](Bubble-sort-example.gif)

(image via [Wikipedia](http://en.wikipedia.org/wiki/Bubble_sort))

#### Due: end of class Tuesday, January 20th to tealsteachers@gmail.com

# Part 1 -- Starter Code (5 points)
Download the starter code from the [bubble sort starter code](bubble_sort_starter.sb2).

You will be writing all of your code in the Stage. Check out the code that is already in the Stage script area before you start adding your own code.

# Part 2 -- Add a Swap Block (15 pts)
Create a new block for the Stage that is called `swap index [x] with index [y]`. The block takes in two integers, `x` and `y`, and swaps the items in list `letters` at those positions.

For example, if `letters = [A, C, D, E, B]` then executing the block `swap index [1] with index [3]` will change `letters` to `[D, C, A, E, B]`.

At the end of the swap block code, call the block `update letters` and wait 1 second (the `wait` block is in the Control category).

# Part 3 - One Iteration (15 pts)
Implement one iteration of bubble sort when the space bar is pressed. That means your code should loop over the list `letters` once and swap any consecutive items that are not in the correct order.

For example, if `letters = [E, B, A, C, D]` then after one iteration, `letters` should be `[B, A, C, D, E]`

# Part 4 -- All Iterations (15 points)
Complete the bubble sort algorithm. Your code should repeat steps 1-3 until it does one full iteration without doing any swaps.

On each iteration, change to the next backdrop so the backdrop displays the iteration number. When the list is sorted, change the background to `party`.

![](sorted_party.png =100px)

# Part 5 -- Style (10 points)
- Variables have meaningful names.
- There are no unused blocks on the screen.
- All of your code is in the Stage sprite.
- You only have one `When space key pressed` block.

# Extra Credit -- Insertion Sort (10 points)
The extra credit is to implement the [Insertion Sort](http://en.wikipedia.org/wiki/Insertion_sort) algorithm.

**Do not change your working bubble sort code.**  Instead, re-download the [starter code](bubble_sort_starter.sb2) and save the file as insertion_sort.sb2.

The insertion sort algorithm is as follows:

1. Assume that the first element is "sorted." This starts the sorted section of your list.
1. Look at the next item and find where is belongs in the sorted list section.
1. Shift all other items down and insert the current item into the correct spot in the sorted section.
1. Repeat steps 1 and 2 until you have incerted every item in the list.

![insertion sort](Insertion-sort-example.gif)

(image via [Wikipedia](http://en.wikipedia.org/wiki/Insertion_sort))
