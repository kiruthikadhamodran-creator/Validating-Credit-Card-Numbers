Algorithm
Use a regular expression to verify:
Starts with 4, 5, or 6.
Contains exactly 16 digits.
Optional hyphens appear only in groups of 4 digits.

Remove hyphens and check for four consecutive repeated digits using:

r'(\d)\1\1\1'
Print:
"Valid" if all conditions are satisfied.
"Invalid" otherwise.
Example

Input

4123456789123456

Output

Valid

Input

4424444424442444

Output

Invalid

Reason: The digit 4 repeats 4 times consecutively.

Time Complexity
O(n) per card number, where n = 16.
Space Complexity
O(1).
