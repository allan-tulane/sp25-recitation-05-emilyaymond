# CMPS 2200 Reciation 5
## Answers

**Name:**___Emily Aymond___


Place all written answers from `recitation-05.md` here for easier grading.



- **1b.**

|      n |   qsort-fixed-pivot |   qsort-random-pivot |   tim-sort |
|--------|---------------------|----------------------|------------|
|    100 |               0.110 |                0.119 |      0.008 |
|    200 |               0.214 |                0.234 |      0.015 |
|    500 |               0.545 |                0.647 |      0.041 |
|   1000 |               1.107 |                1.265 |      0.092 |
|   2000 |               2.380 |                2.698 |      0.171 |
|   5000 |               5.804 |                6.067 |      0.426 |
|  10000 |              10.557 |               11.568 |      0.838 |
|  20000 |              20.836 |               23.317 |      1.718 |
|  50000 |              56.506 |               62.884 |      4.776 |
| 100000 |             116.435 |              131.134 |     10.238 |

<img width="639" alt="Screenshot 2025-03-20 at 3 07 05 PM" src="https://github.com/user-attachments/assets/12439239-75c6-4410-bb0c-53adf3fcc269" />



Selection sort is not included in this table because it kept messing up the appearance of the table but the complexities can be found below.
 
Quicksort average case: O(n log n)
Quicksort worst case: O(n^2)
Selection sort average case: O(n^2)
Selection sort worst case: O(n^2)

- **1c.**
tim-sort can be seen in the table above in 1b. It can be seen it is faster than any of the other algorithms implemented in this lab.
