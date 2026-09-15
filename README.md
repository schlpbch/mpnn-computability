# What Can MPNNs Compute?

Reading notes, in the form of a Beamer slide deck, on:

> Wittig, Vasileiou, Nerem et al., *What Can MPNNs Compute? A Computability
> Hierarchy for Message-Passing Neural Networks*, ICML 2026
> ([arXiv:2602.13106](https://arxiv.org/abs/2602.13106))

The talk asks a training-independent question: given the fixed-depth,
loop-free, recursion-free structure of a message-passing neural network
(MPNN), what class of functions can it represent at all? It places the
answer on the classical recursive-function hierarchy, distinct from
learning-theoretic questions about whether an MPNN can be *trained* to
approximate a target algorithm.

## Contents

- `mpnn-talk.tex` — the slide deck source
- `asc-theme.sty` — shared Beamer theme
- `fonts/` — IBM Plex Sans font files used by the theme
- `Makefile` — build rules

## Building

Requires `lualatex` (e.g. via TeX Live).

```sh
make          # build mpnn-talk.pdf
make clean    # remove auxiliary build files
make distclean # also remove the PDF
```

## Author

Andreas Schlapbach (schlpbch@gmail.com)
