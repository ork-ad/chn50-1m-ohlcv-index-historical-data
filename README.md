# CHN50 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_535_165_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full CHN50 dataset on ork.ad**](https://ork.ad/)

**CHN50 1m OHLCV Stock index historical data** — ultra high-quality 1m OHLCV for **China 50**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **China 50** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **2,535,165** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `CHN50_1m.csv` (148,524 rows, `2026-01-05` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **2,535,165** `1m` rows (~135.14 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2017-07-17` → `2026-07-03`.

## Download sample

**[CHN50_1m.csv](https://github.com/ork-ad/chn50-1m-ohlcv-index-historical-data/blob/main/CHN50_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/chn50-1m-ohlcv-index-historical-data/main/CHN50_1m.csv)) · [GitHub Releases](https://github.com/ork-ad/chn50-1m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/chn50-1m-ohlcv-index-historical-data/](https://ork-ad.github.io/chn50-1m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | China 50 · Stock index | China 50 · Stock index |
| Timeframes | `1m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1m rows | 148,524 | **2,535,165** |
| Size | 8.37 MB | ~135.14 MB |
| Period | `2026-01-05` → `2026-07-03` | `2017-07-17` → `2026-07-03` |
| File | `CHN50_1m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`1m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `1m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`CHN50_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-05T01:01:00Z | 15472.33 | 15472.33 | 15452.52 | 15453.03 | 71 |
| 2026-01-05T01:02:00Z | 15453.03 | 15456.01 | 15452.01 | 15453.03 | 53 |
| 2026-01-05T01:03:00Z | 15453.03 | 15453.53 | 15448.01 | 15448.01 | 30 |
| 2026-01-05T01:04:00Z | 15448.01 | 15451.01 | 15447.02 | 15448.01 | 22 |
| 2026-01-05T01:05:00Z | 15448.01 | 15452.02 | 15448 | 15450.02 | 18 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T20:40:00Z | 14965.84 | 14966.34 | 14965.32 | 14966.34 | 59 |
| 2026-07-03T20:41:00Z | 14966.34 | 14966.34 | 14965.32 | 14966.33 | 147 |
| 2026-07-03T20:42:00Z | 14966.33 | 14966.34 | 14965.33 | 14966.33 | 22 |
| 2026-07-03T20:43:00Z | 14966.33 | 14966.33 | 14966.33 | 14966.33 | 2 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('CHN50_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('CHN50_1m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('CHN50_1m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **CHN50** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **2,535,165** rows at `1m`, plus all other timeframes in the same ZIP.

**[→ Get the full CHN50 dataset on ork.ad](https://ork.ad/)**

---
*GetData · CHN50 1m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-05 UTC*