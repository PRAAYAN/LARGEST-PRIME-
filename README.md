# LARGEST-PRIME-
The prime factors of  are  and .

What is the largest prime factor of a given number ?

Input Format

First line contains , the number of test cases. This is followed by  lines each containing an integer .

Constraints

Output Format

For each test case, display the largest prime factor of .

Sample Input 0

2
10
17
Sample Output 0

5
17
Explanation 0

Prime factors of  are , largest is .
Prime factor of  is  itself, hence largest is .
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#!/bin/python3

import sys


t = int(input().strip())
for a0 in range(t):
    n = int(input().strip())
