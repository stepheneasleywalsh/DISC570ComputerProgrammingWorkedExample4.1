# 🧮 Algorithm: Decide if a Number is Prime

## Problem
Decide whether a given number `X` is a prime number.

## Steps

1. Let **X** be the number you want to check.
2. Set **n = 1**.
3. Create an empty list to store divisors of **X**.
4. If **n divides X exactly**, add **n** to the list.
5. Increase **n by 1**.
6. If **n ≤ X**, go back to step 4.
7. Count how many numbers are in the list.
8. If the count is **exactly 2**, go to step 9. Otherwise, go to step 10.
9. Say: **"It is prime."** ✅ Done.
10. Say: **"It is not prime."** ❌ Done.
