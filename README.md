# AlphaSift track record

Every trading day after the close, a GitHub Action runs each built-in strategy with `--no-llm --save-run` and commits the saved run here. Picks are never edited afterwards; the git history is the timestamped record. Each pick is then measured at T+5 / T+10 / T+20 trading days against its market benchmark.

**Dashboard:** https://alphasift.zhulinsen.tech/ · Code: [ZhuLinsen/alphasift](https://github.com/ZhuLinsen/alphasift) · Updated 2026-11-27T04:22:19+00:00 · 27 saved runs

> For research only, not investment advice. From 2026-11-21, entry uses `next_open` (explicitly tracking one-price limit-up untradable blocks); legacy pre-switch runs used signal-day `close`. Returns deduct round-trip costs, ignore dividends, and small samples are noisy.

## Scorecard (T+5 / T+20)

| Market | Strategy | Runs | T+5 n | T+5 excess | T+5 beat | T+20 n | T+20 excess | T+20 beat |
|---|---|---:|---:|---:|---:|---:|---:|---:|
| cn | 均衡多因子 | 2 | 0 | – | – | 0 | – | – |
| cn | 蓝筹收益质量 | 2 | 0 | – | – | 0 | – | – |
| cn | 资金热度 | 2 | 0 | – | – | 0 | – | – |
| cn | 双低选股 | 2 | 0 | – | – | 0 | – | – |
| cn | 低波质量 | 2 | 0 | – | – | 0 | – | – |
| cn | 趋势质量 | 2 | 0 | – | – | 0 | – | – |
| cn | 超跌反转 | 2 | 0 | – | – | 0 | – | – |
| cn | 稳健价值 | 2 | 0 | – | – | 0 | – | – |
| cn | 缩量回踩 | 2 | 0 | – | – | 0 | – | – |
| cn | 放量突破 | 2 | 0 | – | – | 0 | – | – |
| hk | 全球低估值 | 2 | 0 | – | – | 0 | – | – |
| in | 全球低估值 | 2 | 0 | – | – | 0 | – | – |
| jp | 全球低估值 | 1 | 0 | – | – | 0 | – | – |
| kr | 全球低估值 | 1 | 0 | – | – | 0 | – | – |
| tw | 全球低估值 | 1 | 0 | – | – | 0 | – | – |

## Latest session

- **asia** finished 2026-11-26T19:46:45+00:00: 0/0 strategies ok (15 skipped)
- **us** finished 2026-11-27T04:22:18+00:00: 0/0 strategies ok (2 skipped)

Raw runs: [`data/runs/`](data/runs) · derived site data: [`site/`](site)
