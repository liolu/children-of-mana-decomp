# Childrenmana decompilation (USA)

> **This game moved to [liolu/All-nds-decomp-games](https://github.com/liolu/All-nds-decomp-games/tree/main/games/C/children-of-mana)** (`games/C/children-of-mana`), with its whole history: every Nintendo DS decompilation in one repository, one game downloadable on its own (`python nds.py get children-of-mana`). This repository is archived; issues and pull requests go there.

Nintendo DS, game code `ASEE`. Matching decompilation with Metrowerks mwccarm (compiler version still to be identified: `python tools/probe_compiler.py`).

No game assets in this repository: see `extract/README.md`.

## Progress

<!-- progress:start -->
`████░░░░░░░░░░░░░░░░` **21.12%** of the code matched · data 8.86% · 4607/9012 functions

| Part of the code | Files | Functions | Share of all code |
|---|---|---|---|
| Auto-matched (raw m2c output, to clean up) | 4466 | 4466/4466 | 19.73% |
| Reused from other decompilations, not merged into files yet | 141 | 141/141 | 1.39% |
| Game code: `src/data/` | 966 | 0/0 | 0.00% |

*Updated 2026-11-05 by `python tools/match.py progress` ([DS Decomp Studio](https://github.com/liolu/ds-decomp-studio)). A function counts only when it compiles to the exact same bytes and the ROM still rebuilds byte for byte.*
<!-- progress:end -->

```shell
python tools/configure.py usa
ninja
python tools/match.py status
```

Created from the rayman-rr template. See `AGENTS.md` for the rules.
