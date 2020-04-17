#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) This snippet is a constant, since the size of the input does not affect the runtime.

b) This snippet is logarithmic, it is reducing the size of the input data with "while j < n" portion, which remains pretty efficient even as the input grows.

c) This snippet is being called recursively "bunnies" times until it reaches base case. This is linear ( O(n) ), as each increase to the input adds to the stack, and is generally acceptable in terms of run time.

## Exercise II

The first egg toss would take place at floor (n/2). If the egg breaks, the algorithm would then split the bottom half of floors in half again, or if the egg survived it would instead split the top half of floors in half. Executing a binary type search instead of a linear search to reduce the amount of eggs tossed so we wouldn't have to toss one per floor.

The runtime complexity in this scenario would be an O(log(n)) logarithmic classification. Since each check reduces the amount of inputs being scanned by 2 at every stage, doubling the number of floors only creates one more egg toss scenario. i.e. 8 floors is checked 3 times, and 16 floors is checked 4 times.
