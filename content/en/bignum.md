---
title: "go-bignum"
description: "Correctly rounded big.Float functions and a Go oracle harness. bigfloat is released v0.1.0."
---

go-bignum is the home of arbitrary precision in the parity plan: correctly
rounded `big.Float` functions, number theory, and the Go oracle harness.

| Package | Status | Repository |
| --- | --- | --- |
| bigfloat | released v0.1.0 | [go-bignum/bigfloat](https://github.com/go-bignum/bigfloat) |

## State

From [STATUS.md](https://github.com/go-scikit/roadmap/blob/main/STATUS.md):
v0.1.0 is released: correctly rounded roots, exponentials and logarithms,
trigonometric, hyperbolic and power functions and constants, and the Go oracle
harness. Every function is at or below mpmath's time (0.18–0.97x at 53–200
bits, 0.27–0.92x at 1000 bits;
[docs/perf.md](https://github.com/go-bignum/bigfloat/blob/v0.1.0/docs/perf.md)),
and the results stay correctly rounded against mpmath on 28 840 cases in six
rounding modes.

## Where to read more

- Landing: [go-bignum.github.io](https://go-bignum.github.io/)
- Documentation: [go-bignum.github.io/docs](https://go-bignum.github.io/docs/)
- Organisation: [github.com/go-bignum](https://github.com/go-bignum)
