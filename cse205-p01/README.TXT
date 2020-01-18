The p01-in.txt file in the 'input' folder contains the sample list of numbers from the project docu-
ment. The p01-runs.txt file in the 'output' folder contains the expected (and correct) output for
this input list.

For testing, you should create several different p01-in.txt files containing different lists so you
can try to locate situations in your program where the output file is not as expected, i.e., to find
bugs in your code.

When we grade your project, we will try several different lists to attempt to break your program, so
you might give some thought to what types of unusual lists might cause your program problems.

For example, Software Requirement 1 states that n (the size of the list) will be in [1, 1000] so you
should definitely run your program on a list with 1 element and a list with 1000 elements.

Think about this: if there were 100 elements in the list, what could be the maximum and minimum
values of k? How would the list have to be ordered so the max and mins are reached? Your mindset as
a tester should be "evil genius", with the goal of breaking the program in as many ways as humanly
possible.

I hope you have fun with this project.

Kevin
