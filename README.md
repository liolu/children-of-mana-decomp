# Childrenmana decompilation (USA)

Nintendo DS, game code `ASEE`. Matching decompilation with Metrowerks mwccarm (compiler version still to be identified: `python tools/probe_compiler.py`).

No game assets in this repository: see `extract/README.md`.

## Progress

<!-- progress:start -->
`█░░░░░░░░░░░░░░░░░░░` **6.02%** of the code matched · data 3.53% · 1941/9012 functions

| Part of the code | Files | Functions | Share of all code |
|---|---|---|---|
| Auto-matched (raw m2c output, to clean up) | 1859 | 1859/1859 | 5.13% |
| Reused from other decompilations, not merged into files yet | 82 | 82/82 | 0.89% |
| Game code: `src/data/` | 530 | 0/0 | 0.00% |

*Updated 2026-11-02 by `python tools/match.py progress` ([DS Decomp Studio](https://github.com/liolu/ds-decomp-studio)). A function counts only when it compiles to the exact same bytes and the ROM still rebuilds byte for byte.*
<!-- progress:end -->

```shell
python tools/configure.py usa
ninja
python tools/match.py status
```

Created from the rayman-rr template. See `AGENTS.md` for the rules.
