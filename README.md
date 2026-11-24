# ngkaz-prog-site-generator-speed-01

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/ngkaz-prog/ngkaz-prog-site-generator-speed-01/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/ngkaz-prog/ngkaz-prog-site-generator-speed-01/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in for make.fun's own makefun-site 1.0.0: it answers exactly as makefun-site does on every case, but faster. solve.js is a dependency-free ES module whose run(input) returns, for one generated site, the output tree makefun-site 1.0.0's build returns, as a JSON object of every path it writes and that file's text, byte for byte.

## Run it

```sh
node main.ts
```

main.ts reads every case from /input/cases.json, answers each with run, and writes /output/answers.json. Practice set: 3/3 cases byte-identical to the reference, ~1.6x faster than the house baseline on CPU time.

## Entry

- Repo: ngkaz-prog-site-generator-speed-01
- Owner: ngkaz-prog
- Referral: https://make.fun/r/44s381bx

---

<sub>Entered on [make.fun](https://make.fun/?ref=44s381bx&utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
