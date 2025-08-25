# Calculate-Double-or-Triple

Input: 3 

Output: 9

Question Explanation:

This program determines the behavior of an integer N based on its divisibility by 3. It performs two primary functions:

Checks if N is divisible by 3.
Based on the divisibility, it either triples N if it is divisible by 3 or doubles N if it is not.

Logical Approach:

Read Input:
Read the integer N.

Check Divisibility by 3:
Determine if N is divisible by 3 by using the modulo operator (%). The expression N % 3 equals 0 if N is divisible by 3.

Calculate Output:
If N is divisible by 3, triple N by calculating N * 3. Otherwise, double N by calculating N * 2.

Output:
Print the result, which is either the triple or double of N.

Example for Clarity:

If the input N is 6:

Since 6 is divisible by 3 (6 % 3 = 0), the triple of N is calculated.

The triple of 6 is 18 (6 * 3 = 18).

The output will be 18.

If the input N is 4:

Since 4 is not divisible by 3 (4 % 3 != 0), the double of N is calculated.

The double of 4 is 8 (4 * 2 = 8).
