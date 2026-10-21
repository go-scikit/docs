---
title: "go-approx"
description: "Interpolation, splines and polynomials. interp is released v0.2.0 and poly v0.1.0."
---

go-approx is the home of approximation in the parity plan: interpolation,
splines, polynomials, and later Chebyshev and AAA approximation and scattered
data.

| Package | Status | Repository |
| --- | --- | --- |
| interp | released v0.2.0 | [go-approx/interp](https://github.com/go-approx/interp) |
| poly | released v0.1.0 | [go-approx/poly](https://github.com/go-approx/poly) |

## What is verified

From [STATUS.md](https://github.com/go-scikit/roadmap/blob/main/STATUS.md):
`numpy.interp`, `interp1d`, PCHIP, Akima and `poly1d` are bit-identical to
NumPy and SciPy; splines agree within 1e-15 to 1e-10. `interp` v0.2.0 adds `Splrep`
(FITPACK's legacy `splrep`) and is faster than SciPy on every case measured
except two still open: `RegularGridInterpolator` linear evaluation at 10^3 to
10^4 points (0.95 to 0.98x) and shuffled-query cubic evaluation at 10^4 points
(0.94x). The speed comparison with the Python reference is in
[interp's docs/perf.md](https://github.com/go-approx/interp/blob/main/docs/perf.md).

## Where to read more

- Landing: [go-approx.github.io](https://go-approx.github.io/)
- Documentation: [go-approx.github.io/docs](https://go-approx.github.io/docs/)
- Organisation: [github.com/go-approx](https://github.com/go-approx)
