1. Write out the following explicitly and find the sum

$$\sum_{72}^{i=1} i$$

- 1 x 1 x 1.... x 1 = 1
- 1 + 72 = 73
- 1 + + 1 + 1 .... + 1 = 72
- None of the above

<details>
  <summary>Solution</summary>

The above summation represents the sum of all integers from 1 to 72.
Using the formula for the sum of the first n natural numbers

S~n~ = $\frac{n(n + 1)}{2}$, whre n = 72

Step 1:

Substitute n = 72 in to the formula

S~72~ = $\frac{72(72+ 1)}{2}$

Step 2:

Calculate: S~72~ = 2628

</details>

<br>

2. Write down the value of the next term in the sequence 1,1,2,3,5,8, ...

- 13
- 12
- 8
- None of the above

<details>
  <summary>Solution</summary>

The sequence 1,1,2,3,5,8, is the `Fibonacci sequence`, where each term is the sum of the two preceding terms

The next term after 8 is: 5 + 8 = 13

</details>

<br>

3. Find the n^th^ term of the sequence pattern: 2,5,8,11,14, ... start from n = 1

- n + 3
- None of the options
- n - 3
- 3n + 1
- 3n - 1

<details>
  <summary>Solution</summary>

The sequence 2,5,8,11,14 is an arithmetic sequence wheer each term increases by a constant difference d = 3

The formula for the n-th term of an arithmetic sequence is

a~n~ = a + (n - 1)d, where
`a` is the first term (a = 2)
`d` is the common difference (d = 3)

Step 1: Substitud a = 2 and d = 3

a~n~ = 2 + (n - 1)(3)

Step 2: Simplify

a~n~ = 2 + 3~n~ 3
a~n~ = 3~n~ 1

Step 3: Final answer

3~n~ - 1

</details>

<br>

4. Find the n^th^ term of the arithmetic sequence 14,18, 22, ...

- a~n~ = 14 + 4(n+1) = 4n + 18
- a~n~ = 14 x 4(n-1) = 56n - 56
- a~n~ = 14 + 4(n-1) = 4n + 10
- None of the above

<details>
  <summary>Solution</summary>

a~n~ = a + (n - )d, where `a` = 14 (first term), `d` = 4 (common difference)

Step 1: Substitute a = 14 and d = 4

a~n~ = 14 + (n - 1)(4)

Step 2: Simplify

a~n~ = 14 + 4n - 4
a~n~ = 4n + 10

</details>

<br>

5. Which of the following represent the summation:

$$\sum_{i=1}^{n} (5i^2 + 3i - 1)$$

Select all the apply

- $$5\sum_{i=1}^{n} i^2 + 3\sum_{i=1}^{n} i - \sum_{i=1}^{n} 1 $$
- $$5(\sum_{i=1}^{n} i) ^2  + 3(\sum_{i=1}^{n}) - 1$$
- $\frac{5n(n+1(2n+1))}{6}$ + $\frac{3n(n+1)}{2}$ - n
- None of the above

<details>
  <summary>Solution</summary>

Step 1: Split the summation

$$\sum_{i=1}^{n} (5i^2 + 3i - 1) = 5 \sum_{i=1}^{n} i^2 + 3 \sum_{i=1}^{n} i - \sum_{i=1}^{n} 1$$

This matches Option 1 and 3

</details>

<br>

6. Find the limit of the sequence u~n~ = $\frac{1}{n-1}$ as n tends to ∞

<details>
  <summary>Solution</summary>

Step 1: Write the sequence explicitly

u~n~ = $\frac{1}{n}$ - $\frac{1}{n - 1}$

Step 2: Combine terms using a common denominator

The least common denominator of `n` and `n - 1` is `n(n-1)`. Rewritte the terms

u~n~ = $\frac{(n -1) - n}{n(n - 1)}$

Simplify the numerator

u~n~ = $\frac{1}{n(n - 1)}$

Step 3: Evaluate the limit as n -> ∞

As n -> ∞, the denominator n(n-1) -> ∞ so

u~n~ = 0

</details>

<br>

7. Given a sequence , u~n~ defined by the following sequence pattern 3,5,7,9,1, .....

Which one of the following represents the sum of the first n^th^ term of

$$\sum_{i=1}^{∞}un$$

- n^2^ + 2n
- n^2^ - 2n
- n^2^ + n
- None of the above

<details>
  <summary>Solution</summary>

The given sequence u~n~ = 3,5,7,9 .. is an arithmetic sequence with

- First term a = 3
- Common difference d = 2

To find the sum of the first n trms, we use the formula for the sum of an arithmetic sequence:

S~n~ = $\frac{n}{2}$ (2a + (n -1) d)

Where :

- a is the first term
- d is the common difference
- n is the number of terms

Step 1: Substitute a = 3 and d = 2 into the formula

S~n~ = $\frac{n}{2}$ (2(3) + (n -1)(2))

Step 2: Simplify yhe expression inside the parentheses

S~n~ = $\frac{n}{2}$ (6+ 2n -2)
S~n~ = $\frac{n}{2}$ (4 + 2n)

Step 3: Factor out 2

S~n~ = $\frac{n}{2}$ \* 2(n + 2)
S~n~ = n(n+2)

Step 4: Expand S~n~

S~n~ = n^2^ + 2n

</details>

<br>

8. Find S~1~, S~2~ and S~3~ and S~4~ for the following recurrence relation
   S~n+1~ = 2(S~n~ + 1) and S~1~ = 1

- S~1~ = 1, S~2~ = 4, S~3~ = 10 and S~4~ = 22
- S~1~ = 0, S~2~ = 2, S~3~ = 6 and S~4~ = 14
- S~1~ = 1, S~2~ = 4, S~3~ = 25 and S~4~ = 25
- None of the above

9. Use mathematical induction to prove that
   p(n) = 1^2^ and 2^2^ and 3^2^ + ... + n^2^ = $\frac{n(n+1)(2n+1)}{6}$ for all positive integers `n`

Determine all the correct steps

- We assume that p(k + 1) is true
- We first show that p(1) is true
- We now assume that p(n+1) is true
- We now assume that p(k) is true
- We show that p(k+1) is true by adding (k+1)^2^ to both sides
- Simplify the terms and check if both sides are the same

10. The formula for the sum of `n` terms of a geometric progression is

- S~n~ = a~0~ + (n - 1) \* d
- S~n~ = $\frac{a(1 + r^n)}{(1 + r)}$
- S~n~ = $\frac{a(1 - r^n)}{(1 - r)}$
- None of the above
