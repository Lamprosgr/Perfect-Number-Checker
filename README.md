# Perfect Number Checker
## Definition
A Perfect Number is a positive integer that is equal to the sum of its positive divisors, excluding itself. For example:

- 6 is a perfect number because its divisors are 1, 2, and 3, and 1 + 2 + 3 = 6.
- 28 is a perfect number because its divisors are 1, 2, 4, 7, and 14, and 1 + 2 + 4 + 7 + 14 = 28.

## Explanation
1. Input Validation: The method first checks if the input number is positive. If the number is zero or negative, it immediately returns false since a perfect number must be a positive integer.
2. Finding Divisors: It iterates through all integers from 1 to number / 2. If a number is a divisor of the input number, it adds it to the sum.
3. Sum Comparison: After summing all divisors, it checks if the sum equals the input number. If they are equal, the method returns true; otherwise, it returns false.


## Examples
- System.out.println(isPerfectNumber(6));   // Output: true
- System.out.println(isPerfectNumber(28));  // Output: true
- System.out.println(isPerfectNumber(12));  // Output: false
- System.out.println(isPerfectNumber(-5));  // Output: false
- System.out.println(isPerfectNumber(0));   // Output: false
