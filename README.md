**# BCD-7-SEGMENT**
USING VERILOG:

![decimal-or-bcd-adder2](https://github.com/panda12384/BCD-7-SEGMENT/assets/160568759/6ccf8c09-0f33-48fb-8883-6e839568e4ef)


A Binary-Coded Decimal (BCD) adder is a digital circuit that adds BCD numbers. BCD is a form of binary encoding where each digit of a decimal number is represented by its own 4-bit binary sequence. A BCD adder ensures that the result of adding two BCD numbers is also a valid BCD number.

Key Concepts:

Each decimal digit (0-9) is represented by a 4-bit binary number (0000 to 1001).
Values 1010 to 1111 are invalid in BCD.

BCD Addition:

Add two 4-bit BCD numbers using binary addition.
If the sum is greater than 9 (1001 in binary) or a carry is generated, add 6 (0110 in binary) to the sum to correct it.


BCD Adder Circuit:

Add the two BCD numbers using a 4-bit binary adder.
Check if the result is greater than 9 or if there is a carry-out.
If correction is needed, add 6 to the result.

**The output:**

![Screenshot 2024-07-04 133716](https://github.com/panda12384/BCD-7-SEGMENT/assets/160568759/54ff2197-c51a-412e-8b4f-f54afd0a3142)
