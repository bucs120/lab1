#### CS 120 - Spring 2019
# Lab 1 - Working with Binary
## Due Date: In Lab

### Provided Files
* _Files_
    * N/A

**You must demo to the TA by the end of your lab.**

### Guidelines

Although this is an individual lab assignment, it is permissible to consult with classmates to ask general questions and to get help. You may also research online for additional resources; however, you must be able to explain how you got your answers to the TA to complete the lab.


_In this lab, you will learn to:_

* Work with binary values
* Convert from binary to decimal and vice versa

Look for these icons!


## Part A: Turing Machine

Assume you have a Turing machine, as discussed in class, with the instructions Left, Right, Read, Write. Each memory location is 1 bit.
1. A single read operation reads in 4 sequential bits starting from the head location.
    * Successive reads adds to the value currently in memory
2. A single write operation writes the current state value as 4 bits in sequential memory locations.
    * After any write operation, the machine state is cleared to 0.
3. A single Left operation moves the head 1 memory location left.
4. A single Right operation moves the head 1 memory location right.

We would like the Turing Machine to complete the following operation:
* Once the Turing Machine has read in 4 bits, it treats these bits as a 4 bit unsigned binary number, and adds 1 to the value. It then overwrites the original 4 bits with the newly incremented value.
    * Write the sequence of instructions and machine state required to perform this operation.
    * What happens when all the bits are 0?


## Part B: Binary Conversions

1. Convert the following decimal numbers into 8-bit unsigned binary

|24|32|15|1|
|-----|-----|-----|-----|

2. Convert the following decimal numbers into 8-bit signed magnitude

|-24|-32|-15|-1|
|-----|-----|-----|-----|

3. Do the following addition problems, where the numbers are 5-bit unsigned integers. With a 5-bit result, is the number correct, or do you have an overflow?

|&nbsp;&nbsp;10110<br>+00101 |&nbsp;&nbsp;10101<br>+00111 |&nbsp;&nbsp;10100<br>+00111 |&nbsp;&nbsp;01111<br>+11110 |
|-|-|-|-|

4. Convert the 8 bit unsigned binary numbers below into decimal?

|10101010 |01110100 |11111111 |10000000 |
|-|-|-|-|

## Part C: Submission

Ask your TA to demo. The TA will ask you to show your answers, and may ask you to explain how you got an answer. After the TA marks you as having completed the lab, you may leave.
