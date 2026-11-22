# site-generator-speed-01

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/bimasetmuse61/site-generator-speed-01/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/bimasetmuse61/site-generator-speed-01/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in for makefun-site 1.0.0 (site-generator-speed-01-run-20261122):
`solve.js` reimplements the reference generator — its front matter, template
dialect, Markdown subset, slug rule and report — byte for byte, with the hot
paths rewritten for speed (chunked inline Markdown, cached slugifying, array
template rendering). `main.ts` is the harness driver: it reads every case from
`/input/cases.json`, answers each with `run`, and writes `/output/answers.json`.

## Run it

```sh
node main.ts
```

Set `MAKEFUN_INPUT_DIR` and `MAKEFUN_OUTPUT_DIR` before running.

---

<sub>Entered on [make.fun](https://make.fun/?ref=k6h0aem7&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
