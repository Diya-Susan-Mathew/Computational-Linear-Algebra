## Pseudocode for Linear Algebra

``` python
```

$$
\begin{bmatrix}
1 & 2 & 3 \\
3 & 4 & 5 \\
5 & 6 & 7
\end{bmatrix}
$$

## Pseuodocode for Solution of System of Equations
``` python
FUNCTION Solution(A,b):
  Create Augmented matrix: k = [A|b]
  Reduce in Row Reduced Echelon form
  Rank = no of non zero rows of row reduced echelon form
  IF Rank(k) != Rank(A):
    print("System is inconsistent")
  ELSE IF:
    Solve using back substitution
END FUNCTION
```


