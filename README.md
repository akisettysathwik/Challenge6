# Challenge6

Problem Statement:
A smart-campus activity monitor records the number of visits over several time slots. Your task is to write a C program that studies the sequence, finds meaningful patterns, and then rotates the data for a cyclic report. The important part is to plan the logic before coding and to handle unusual cases correctly.
Read N activity readings into a one-dimensional array and complete every task below. N must be between 5 and 12 inclusive. Each reading must be an integer from 0 to 1000 inclusive. If N or a reading is invalid, ask again until valid input is entered.

Algorithm:
1.  Start
2.  Read N and validate that it is between 5 and 12. If invalid, ask again.
3.	Read N array elements. Validate that every reading is between 0 and 1000.
4.	Display the original array.
5.	Calculate the sum, average, minimum, and maximum of the readings.
6.	Find the second-largest distinct value. If it does not exist, display a message.
7.	Count the local peaks by comparing each interior element with its two neighbours.
8.	Find the longest strictly increasing contiguous run in the array.
9.	Read the integer K and normalize it using K % N. If the result is negative, add N.
10.	Rotate the array right by the normalized number of positions using three reversals, without using a second array.
11.	Display the rotated array.
12.	Read the last two digits R of the registration number.
13.	Calculate \(D=(R\%9)+1\).
14.	Count the values in the rotated array that are exactly divisible by D.
15.	Display D and the divisible-value count.
16.	Stop
