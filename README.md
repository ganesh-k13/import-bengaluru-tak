# How NumPy Divides Integers Really Fast

Talk for **import_ bengaluru** (BangPypers), 6 September 2026.

A deep dive into NumPy's integer division: the multiply-and-shift trick
(`libdivide`), SIMD universal intrinsics for cross-architecture speed, and the
regression I shipped along the way.

Backing PRs: `#17727 · #18075 · #18766 · #18751 · #19135 · #21507 · #21727`

## Build

Slides are a [Quarto](https://quarto.org) Reveal.js deck.

```bash
# Live preview with hot reload
quarto preview slides.qmd

# Render to a standalone HTML deck (in _output/)
quarto render slides.qmd

# Export a PDF (needs Chrome/Chromium)
quarto render slides.qmd --to pdf
```

## Notes

- `images/benchmark.png` is a placeholder — replace it with the real
  benchmark chart from PR #17727 / #18075 before presenting.
- Speaker notes are embedded in the deck (press `S` in the browser).
