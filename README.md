# Happy numbers

A happy number is a number defined by the following process: Starting with any positive integer, replace the number by the sum of the squares of its digits in base-ten, and repeat the process until the number either equals 1 (where it will stay), or it loops endlessly in a cycle that does not include 1. Those numbers for which this process ends in 1 are happy numbers, while those that do not end in 1 are unhappy numbers (or sad numbers).

## Overview
More formally, given a number n = n0, define a sequence n1, n2, ... where ni+1 is the sum of the squares of the digits of ni. Then n is happy if and only if there exists i such that ni = 1.

If a number is happy, then all members of its sequence are happy; if a number is unhappy, all members of the sequence are unhappy.

For example, 19 is happy, as the associated sequence is:

1^2 + 9^2 = 82

8^2 + 2^2 = 68

6^2 + 8^2 = 100

1^2 + 0^2 + 0^2 = 1.

Refs Wikipedia (https://en.wikipedia.org/wiki/Happy_number)
