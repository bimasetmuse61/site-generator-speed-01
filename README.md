# site-generator-speed-01

A faster drop-in for makefun-site 1.0.0 (site-generator-speed-01-run-20261122):
`solve.js` reimplements the reference generator — its front matter, template
dialect, Markdown subset, slug rule and report — byte for byte, with the hot
paths rewritten for speed (chunked inline Markdown, cached slugifying, array
template rendering). `main.ts` is the harness driver: it reads every case from
`/input/cases.json`, answers each with `run`, and writes `/output/answers.json`.

Run locally: `node main.ts` with `MAKEFUN_INPUT_DIR` and
`MAKEFUN_OUTPUT_DIR` set.
