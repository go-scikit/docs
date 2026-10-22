---
title: "go-scikit documentation"
linkTitle: "Home"
type: docs
cascade:
  type: docs
description: "The scientific stack for Go, in pure Go (CGO=0), and the organisations that extend it towards MATLAB and Mathematica."
---

**go-scikit is the umbrella over the organisations that make up a scientific
stack for Go.** Each one is a library, or a few, with its own site,
documentation and release cycle. There is no cgo and no C library: one
`go build` gives a static binary. Where a library is slower or less accurate
than its Python reference, its own documentation says so.

## The established organisations

| Organisation | What it is | Landing | Documentation |
| --- | --- | --- | --- |
| [go-ndarray](https://github.com/go-ndarray) | N-dimensional arrays, `numpy.linalg`, `numpy.fft`, `numpy.random` | [site](https://go-ndarray.github.io/) | [docs](https://go-ndarray.github.io/docs/) |
| [go-fft](https://github.com/go-fft) | `numpy.fft` and `scipy.fft` equivalents | [site](https://go-fft.github.io/) | [docs](https://go-fft.github.io/docs/) |
| [go-numerics](https://github.com/go-numerics) | optimisation, quadrature and ODE solvers, special functions | [site](https://go-numerics.github.io/) | [docs](https://go-numerics.github.io/docs/) |
| [go-statistics](https://github.com/go-statistics) | distributions, descriptive statistics, statistical tests | [site](https://go-statistics.github.io/) | [docs](https://go-statistics.github.io/docs/) |
| [go-dataframe](https://github.com/go-dataframe) | labelled tables | [site](https://go-dataframe.github.io/) | [docs](https://go-dataframe.github.io/docs/) |
| [go-plot](https://github.com/go-plot) | matplotlib-class figures | [site](https://go-plot.github.io/) | [docs](https://go-plot.github.io/docs/) |
| [go-notebook](https://github.com/go-notebook) | compiled, reactive Go notebooks | [site](https://go-notebook.github.io/) | [docs](https://go-notebook.github.io/docs/) |

## The parity-plan organisations

The [roadmap](https://github.com/go-scikit/roadmap) plans feature parity with
MATLAB and Mathematica. Wave 1 is under way, in four organisations:

| Organisation | Package | Status | Pages |
| --- | --- | --- | --- |
| go-approx | [interp](https://github.com/go-approx/interp) | released v0.2.0 | [go-approx]({{< relref "approx" >}}) |
| go-approx | [poly](https://github.com/go-approx/poly) | released v0.1.0 | [go-approx]({{< relref "approx" >}}) |
| go-dsp | [signal](https://github.com/go-dsp/signal) | released v0.1.0 | [go-dsp]({{< relref "dsp" >}}) |
| go-sparse | [sparse](https://github.com/go-sparse/sparse) | released v0.1.0 | [go-sparse]({{< relref "sparse" >}}) |
| go-bignum | [bigfloat](https://github.com/go-bignum/bigfloat) | released v0.1.0 | [go-bignum]({{< relref "bignum" >}}) |

The other organisations of the plan (go-symbolic, go-mlkit, go-autodiff,
go-geometry, go-fem, go-graphalgo, go-control, go-units, go-sciio) are
planned; nothing is released there.

"Released" means a tag exists. The status of every item, with its evidence, is
in [STATUS.md](https://github.com/go-scikit/roadmap/blob/main/STATUS.md).

## Where else

- The portal: [go-scikit.github.io](https://go-scikit.github.io/).
- The plan: [go-scikit/roadmap](https://github.com/go-scikit/roadmap) (PLAN.md,
  STATUS.md, bibliography).
- The marks: [go-scikit/brand](https://github.com/go-scikit/brand).
