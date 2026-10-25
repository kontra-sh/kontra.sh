# kontra.sh

The static site behind `https://kontra.sh`, served by GitHub Pages:

- `kontra.sh/kontra` is the Go module path of [medmahmoudi26/kontra](https://github.com/medmahmoudi26/kontra) (D48): `/kontra/…?go-get=1` answers with its `go-import` and `go-source` tags. `404.html` carries the same tags, so any package path under the module resolves.
- `https://kontra.sh/ext/{escrow,sealed,input-schema}/v1` are the A2A extension URIs; each page points at its spec.
