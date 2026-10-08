# MIT 18.06SC Linear Algebra

Self-study notes, and worked problem sets for **MIT 18.06SC Linear Algebra** (Fall 2011), taught by Prof. Gilbert Strang.

**Course:** [ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011](https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/)

---

## Textbook

**Gilbert Strang — *Introduction to Linear Algebra***
Wellesley–Cambridge Press
[math.mit.edu/~gs/linearalgebra](http://math.mit.edu/~gs/linearalgebra/)

The course was taught against the **4th edition**, and OCW gives suggested readings for both the 4th and 5th editions. These notes work from the **5th edition**.

---

## Course Structure

### Unit I — `Ax = b` and the Four Subspaces

The geometry of linear equations · An overview of key ideas · Elimination with matrices · Multiplication and inverse matrices · Factorization into `A = LU` · Transposes, permutations, vector spaces · Column space and nullspace · Solving `Ax = 0`: pivot variables and special solutions · Solving `Ax = b`: row reduced form `R` · Independence, basis and dimension · The four fundamental subspaces · Matrix spaces, rank 1, small world graphs · Graphs, networks, incidence matrices

### Unit II — Least Squares, Determinants and Eigenvalues

Orthogonal vectors and subspaces · Projections onto subspaces · Projection matrices and least squares · Orthogonal matrices and Gram–Schmidt · Properties of determinants · Determinant formulas and cofactors · Cramer's rule, inverse matrix and volume · Eigenvalues and eigenvectors · Diagonalization and powers of `A` · Differential equations and `exp(At)` · Markov matrices and Fourier series

### Unit III — Positive Definite Matrices and Applications

Symmetric matrices and positive definiteness · Complex matrices and the FFT · Positive definite matrices and minima · Similar matrices and Jordan form · Singular value decomposition · Linear transformations and their matrices · Change of basis and image compression · Left and right inverses, pseudoinverse

---

## Repository Layout

```
.
├── problems/       # Worked problem sets, by lecture
├── notes/          # Lecture notes and conceptual write-ups
└── README.md
```

---

## Edition Mapping

Verified correspondences for the Unit III lectures:

| Lecture | Topic | 4th ed. | 5th ed. |
|---|---|---|---|
| 28 | Similar Matrices and Jordan Form | 6.6 | **6.2** |
| 29 | Singular Value Decomposition | 6.7 | **7.1, 7.2** |
| 30 | Linear Transformations and their Matrices | 7.1 | **8.1** |
| 31 | Change of Basis; Image Compression | 7.2 | **8.2** |
| 33 | Left and Right Inverses; Pseudoinverse | 7.3 | **7.4** (see note) |

---

## Attribution

Course materials © Massachusetts Institute of Technology, released under CC BY-NC-SA 4.0 via MIT OpenCourseWare.

The textbook is © Gilbert Strang, Wellesley–Cambridge Press. It is not openly licensed and no textbook content is redistributed here — problems are referenced by section and number only.

---

## A Note on Provenance

These are personal study notes. The handwritten problem sets are my own working.

Section summaries were drafted with AI assistance, then reviewed and corrected
