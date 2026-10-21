# go-scikit/docs

The documentation site of the [go-scikit](https://github.com/go-scikit)
umbrella, served at <https://go-scikit.github.io/docs/>.

Hugo with the [tannevaled/hextra](https://github.com/tannevaled/hextra) fork
(submodule `themes/hextra`, pinned at v0.16.0) and the
[go-scikit/brand](https://github.com/go-scikit/brand) marks (submodule
`branding`). Each documentation version is a separate build published to the
`gh-pages` branch by `.github/workflows/docs.yml`; the version label is the
newest minor among `params.libraries` in `hugo.yaml`.

- Landing: <https://go-scikit.github.io/>
- Roadmap and status: <https://github.com/go-scikit/roadmap>

## Build

```sh
git submodule update --init
sh themes/hextra/scripts/page-history.sh > data/pagehistory.json
hugo server
```

BSD-3-Clause.
