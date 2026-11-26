---
title: "go-sparse"
description: "Sparse containers, orderings and iterative solvers. sparse is released v0.3.2."
---

go-sparse is the home of sparse linear algebra in the parity plan: sparse
containers, orderings, iterative solvers, a quasi-definite sparse LDL^T
factorisation (`ldl`, a port of QDLDL), and later general direct solvers and
sparse eigensolvers.

| Package | Status | Repository |
| --- | --- | --- |
| sparse | released v0.3.2 | [go-sparse/sparse](https://github.com/go-sparse/sparse) |

## What is verified

From [STATUS.md](https://github.com/go-scikit/roadmap/blob/main/STATUS.md):
iteration counts equal SciPy's for CG, GMRES, MINRES and LSQR. Six measured
spmv, CG and GMRES cases are at or below SciPy's time. `ldl` is 1.06 to 1.21x
slower than C QDLDL v0.1.9 on the AMD rows, which is an open defect. The
refbench table of the package is not yet timed.

## Where to read more

- Landing: [go-sparse.github.io](https://go-sparse.github.io/)
- Documentation: [go-sparse.github.io/docs](https://go-sparse.github.io/docs/)
- Organisation: [github.com/go-sparse](https://github.com/go-sparse)
