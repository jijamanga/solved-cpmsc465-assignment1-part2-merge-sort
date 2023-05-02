Download Link: https://assignmentchef.com/product/solved-cpmsc465-assignment1-part2-merge-sort
<br>
Implement merge-sort to sort an array.

# Input

Two lines, the first line gives only one number `n`, the number of integers in the array. And the second line gives `n` numbers which arethe `n` integers in the array. All numbers are separated by space.

You can assume that 0 &lt;= n &lt;= 10000, and that each number in the arrarysare in the range of [-2147483648, 2147483647].

Your code should read the input from standard input (e.g. using functions `input()/raw_input()` in Python and `cin/scanf` in C++).

# Output

One line, describing the sorted array, in ascending order.There should be `n` integers in a line give all numbers in the sorted array (in ascending order).All numbers should be separated with space.(You don’t need to output the size of the array `n`.)

Your code should write the output to standard output (e.g. using functions `print` in Python and `cout/printf` in C++).

# Requirement

Your algorithm should run in O(nlogn) time. You are not allowed to call any in-built sort function.

Time limtation: 5 seconds.

Memory limitation: 1.0 GB.

# Environment

Your code will be running on Ubuntu 18.04.5.

Now only accept C++ and Python2/Python3 code, g++ version 7.5.0 and Python versions are Python 2.7.17 and Python 3.6.9.

# Examples and Testing

Some examples (e.g., input-x.txt and output-x.txt, x = 1, 2) are provided.For Python code, try the following to test your code“`python ./solution.py &lt; input-x.txt &gt; my-output-x.txt“`For C++ code, try the following to test your code“`g++ -o mybinary solution.cpp./mybinary &lt; input-x.txt &gt; my-output-x.txt“`

Your output `my-output-x.txt` needs to be *match exactly* to the given `output-x.txt`.On Unix-based systems you can use `diff` to compare them:“`diff my-output-x.txt output-x.txt“`On Windows you can use `fc` to compare them:“`fc my-output-x.txt output-x.txt“`


