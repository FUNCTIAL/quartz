---
tags:
  - Programming
---

The larger the function, the less efficient it get.
Common Growth Rate (Fastest → Slowest)

| Function | Growth Rate |
| -------- | ----------- |
| 1        | Constant    |
| logN     | Logarithmic |
| log2N    | Log-squared |
| N        | Linear      |
| NlogN    | Log-Linear  |
| N2       | Quadratic   |
| N3       | Cubic       |
| 2N       | Exponential |



Code → f(n) = 3N+C+6 → O(n)

Prove that $f(n) = 3n+6$, is $O(n)$, for all $n > k$

```
```3n+6 =< c*n
6=< c*n -3n
6=< n(c-3)
n=>6/c-3

k=1
c=9

p35
f(n)= O(n*m)
```

i = 1;
while(i < n){
a = a + 1;
i = i * 2;
}

f(n) = O(log(n))

---
# References
1. 