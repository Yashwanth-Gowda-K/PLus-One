This repository contains the solution for the Plus One problem on LeetCode.

Problem Overview:
The task is to add 1 to a number represented by a list of digits. The number is non-negative and the digits are stored in reverse order (e.g., [1, 2, 3] represents the number 321). The solution needs to handle cases such as when the digits contain a carry (e.g., 999 turning into 1000).
Solution
The solution is implemented in Python and works as follows:
Start from the last digit and move backwards through the list.
If the digit is less than 9, simply increment it by 1 and return the updated list.
If the digit is 9, set it to 0 and continue to the next digit.
Edge Case Handling: If all digits are 9, the result will be 100...0.
** Usage**
To use the solution, simply call the plusOne() method, passing a list of digits.
