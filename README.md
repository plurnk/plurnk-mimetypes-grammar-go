# @plurnk/plurnk-mimetypes-grammar-go

Pre-built `tree-sitter-go` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-go
```

## what's in here

- **`go.wasm`** — pre-built from the pinned upstream [tree-sitter-go](https://github.com/tree-sitter/tree-sitter-go) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `go.wasm` is built from the upstream tree-sitter-go grammar; see the pinned commit for that project's attribution.
