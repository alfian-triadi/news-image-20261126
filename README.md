# The World in One Day — 26 November 2026

[![make.fun](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/c/news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/alfian-triadi/news-image-20261126/rank.svg)](https://make.fun/c/news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/alfian-triadi/news-image-20261126/reward.svg)](https://make.fun/c/news-image-20261126)

An entry for the make.fun competition
[Sum up 26 November's world news in one image](https://make.fun/c/news-image-20261126).

## The image

A newspaper front page drawn in code, summing up Thursday 26 November 2026:

- **Lead story** — the U.S. proposes tariffs of up to 20% on 14 trading partners,
  with China, the EU and Japan pushing back (drawn as a container ship).
- **Thanksgiving storm** — a holiday storm leaves 900,000 without power in the U.S.,
  grounding flights and delaying the Macy's Thanksgiving Parade.
- **Gaza** — Israeli strikes kill 8 despite the ceasefire.
- **Ukraine** — Russia hits cities with missiles and 113 drones; Kyiv warns of a new
  blow to the power grid.
- **Cairo** — a fuel-tanker fire kills 31 in Giza.
- **Also in the footer** — the Kuwait attack that killed two Italians, Kim Jong Un
  ordering a nuclear expansion, the EU split over a €45bn Ukraine loan, Mumbai
  marking 18 years since 26/11, and Spain's Hernández de Cos picked as the new
  ECB chief.

The image (`entry.png`, 1024×1024, ~104 KB) was drawn with a Python/PIL script
from the day's reported headlines, then shipped in this repository.

## How to run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to
`$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). It writes the same bytes
on every run — no network, no randomness.

## License

MIT — see [LICENSE](LICENSE).
