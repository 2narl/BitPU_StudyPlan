# Mathematical Induction

Mathematical induction is used to prove statements for all positive integers or another specified integer range.

## Standard structure

Suppose we want to prove `P(n)`.

### 1. Base case
Verify `P(1)`.

### 2. Induction hypothesis
Assume `P(k)` is true.

### 3. Induction step
Using the hypothesis, prove `P(k+1)`.

### 4. Conclusion
Therefore, `P(n)` is true for all `n≥1`.

## Example

Prove:

`1+2+3+...+n = n(n+1)/2`

For `n=1`:

`1 = 1(2)/2 = 1`

Assume:

`1+2+...+k = k(k+1)/2`

Then:

`1+2+...+k+(k+1)`
`= k(k+1)/2 +(k+1)`
`= (k+1)(k+2)/2`

Therefore the formula is true for `k+1`.

Hence, by mathematical induction,

`1+2+...+n = n(n+1)/2`.
