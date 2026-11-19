# Contributing to Harmonic DSP

Thanks for helping. Small, focused changes are easiest to review.

## Getting set up

```bash
git clone https://github.com/shanthoshkv/Harmonic-DSP
```

## Check your change

```bash
test -s README.md && test -f LICENSE && test -f docs/demo.gif
```

This repository holds documentation only. The tool itself is `fourier_enhanced.html` in the [shanthoshkv.github.io](https://github.com/shanthoshkv/shanthoshkv.github.io) repository, so code changes to the analyser belong there.

## Pull requests

1. Open an issue first for anything bigger than a bug fix or doc tweak.
2. Branch from `main`, keep the diff small, one concern per PR.
3. Make sure the check above passes and CI is green.
4. Describe what changed and why. Add a line to `CHANGELOG.md` under **Unreleased** for user-visible changes.

## Good first issues

Look for the [`good first issue`](https://github.com/shanthoshkv/Harmonic-DSP/labels/good%20first%20issue) label. Comment on one to claim it.

## Questions

Use [Discussions](https://github.com/shanthoshkv/Harmonic-DSP/discussions) for questions and ideas, Issues for bugs and concrete requests.

By contributing you agree your work is released under this repository's license.
