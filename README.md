# One Million Divs

> **Try it now:** https://stephenlb.github.io/one-million-divs/

Lots of users changing the colors of each DIV in real-time.

- `index.html` — optimized experience (fewer divs)
- `one-million-divs.html` — the full one million divs

## Benchmark: innerHTML vs appendChild

1. `divs.innerHTML += "more divs"`
2. `divs.appendChild()` — WINNER!

## Challenges

- ✅ Too many divs to render (browser performance)
- ✅ Storage and retrieval (chunked into 5K chunks)
- Compression (bitmap binary)

## Features

- ✅ Color theme / color picker
- ✅ Multi-user live collaboration
