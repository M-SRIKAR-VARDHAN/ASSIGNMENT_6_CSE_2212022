# ASSIGNMENT-6-CSE-2212022 BY SRIKAR VARDHAN 
This repository contains the codes/solution of assignment 6.

*1)Write a program to generate prime numbers using the Sieve of Eratosthenes method*
 
https://github.com/M-SRIKAR-VARDHAN/ASSIGNMENT_6_CSE_2212022/commit/47d63e3679556ec0a20e7aa24e08283cfdde6485
 
Compilation:

`$gcc que1_sieveprime.c`

Running the code:

`$./a.out`

APPROACH-

The Sieve of Eratosthenes is an algorithm that can be used to generate a list of all prime numbers up to a given number.
It is named after the ancient Greek mathematician Eratosthenes, who is credited with developing the algorithm.

Here is how the Sieve of Eratosthenes works:

1) Create a list of consecutive integers from 2 to n (where n is the maximum number you want to check for primality).

2) Set p equal to 2, the first prime number.

3) Starting at p^2, count up in increments of p and mark each of these numbers greater than or equal to p^2 itself in the list.
   These numbers will be 2p, 3p, 4p, etc.; mark them as composite (i.e., not prime).

4) Find the first number greater than p in the list that is not marked. 
   If there is no such number, stop. Otherwise, let p now equal this number (which is the next prime),
   and repeat from step 3.

For example, to find all the prime numbers up to 10, we would do the following:

1) Create a list of integers from 2 to 10: 2, 3, 4, 5, 6, 7, 8, 9, 10.

2) Set p equal to 2, the first prime number.

3) Starting at 4 (which is p^2), count up in increments of 2 (which is p) and mark each of these numbers as composite: 4, 6, 8, 10.

4) The next number in the list that is not marked is 3, so set p equal to 3.

5) Starting at 9 (which is p^2), count up in increments of 3 and mark each of these numbers as composite: 9.

6) The next number in the list that is not marked is 5, so set p equal to 5.

7) Since there are no more numbers in the list to mark, stop.

The resulting list would be: 2, 3, 5, 7, which are the prime numbers up to 10.

**2)Write a program to generate a random one-time password of eight characters long. The password
should contain at least one small letter, one capital letter, one symbol, and one digit.**

 https://github.com/M-SRIKAR-VARDHAN/ASSIGNMENT_6_CSE_2212022/commit/5b68b98100da5abf12b87313b0eef74cb5b3e27e

Compilation:

`$gcc que2_otp.c`

Running the code:

`$./a.out`

**3)Given two array X[2][n] and Y [2][n] containing random numbers, i.e., 2 rows and n columns.
Write a program to solve the following equation**


 https://github.com/M-SRIKAR-VARDHAN/ASSIGNMENT_6_CSE_2212022/commit/8b6f90314ccd1a2d911f4260a4ba7312367cc4c2
 
Compilation:

`$gcc question_3.c`

Running the code:

`$./a.out`

**4)Given an array A[] containing n random numbers. Write a program to find the mean, variance,
and standard deviation of the given array.**

 https://github.com/M-SRIKAR-VARDHAN/ASSIGNMENT_6_CSE_2212022/commit/2896c509d5b84bd779fa13c0f7bd4e0e2fda3d41
 
 Compilation:

`$gcc question4_stddev.c`

Running the code:

`$./a.out`
