---
title: "go-approx"
description: "Interpolation, splines and polynomials. interp and poly are released v0.1.0."
---

go-approx is the home of approximation in the parity plan: interpolation,
splines, polynomials, and later Chebyshev and AAA approximation and scattered
data.

| Package | Status | Repository |
| --- | --- | --- |
| interp | released v0.1.0 | [go-approx/interp](https://github.com/go-approx/interp) |
| poly | released v0.1.0 | [go-approx/poly](https://github.com/go-approx/poly) |

## What is verified

From [STATUS.md](https://github.com/go-scikit/roadmap/blob/main/STATUS.md):
`numpy.interp`, `interp1d`, PCHIP, Akima and `poly1d` are bit-identical to
NumPy and SciPy; splines agree within 1e-15 to 1e-10. The remaining `interp`
gaps are in progress. The speed comparison with the Python reference is in
[interp's docs/perf.md](https://github.com/go-approx/interp/blob/main/docs/perf.md).

## Where to read more

- Landing: [go-approx.github.io](https://go-approx.github.io/)
- Documentation: [go-approx.github.io/docs](https://go-approx.github.io/docs/)
- Organisation: [github.com/go-approx](https://github.com/go-approx)
