# JPN225 1h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-98_600_rows-blue)](https://getdata.finance/datasets/jpn225) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/jpn225)

### -> [**Download the full JPN225 dataset on getdata.finance**](https://getdata.finance/datasets/jpn225)

**JPN225 1h OHLCV index historical data** — ultra high-quality 1h OHLCV for **Nikkei 225**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1h OHLCV** for **Nikkei 225** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/jpn225) · **98,600** `1h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1h` sample updated in sync

> **Sample on GitHub** · `JPN225_1h.csv` (3,025 rows, `2026-03-26` -> `2026-09-25`, 205.77 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/jpn225)** — **98,600** `1h` rows (full `1m`: 4,718,919), **11 timeframes**, `2008-09-01` -> `2026-09-25`.

## Download sample

**[JPN225_1h.csv](https://github.com/getdata-finance/jpn225-1h-ohlcv-index-historical-data/blob/main/JPN225_1h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/jpn225-1h-ohlcv-index-historical-data/main/JPN225_1h.csv)) · [GitHub Releases](https://github.com/getdata-finance/jpn225-1h-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/jpn225-1h-ohlcv-index-historical-data/](https://getdata-finance.github.io/jpn225-1h-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/jpn225](https://getdata.finance/datasets/jpn225)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/jpn225))** |
|---|--:|---|
| Instrument | Nikkei 225 · Index | Nikkei 225 · Index |
| Timeframes | `1h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1h rows | 3,025 | **98,600** |
| Size | 205.77 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Period | `2026-03-26` -> `2026-09-25` | `2008-09-01` -> `2026-09-25` |
| File | `JPN225_1h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Coverage report | — | [JPN225 coverage](https://getdata.finance/coverage/jpn225) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/jpn225)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1h` sample · [getdata.finance](https://getdata.finance/datasets/jpn225) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`JPN225_1h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T03:00:00+00:00 | 53442.31 | 53707.31 | 53422.79 | 53527.81 | 3167 |
| 2026-03-26T04:00:00+00:00 | 53527.81 | 53567.3 | 53317.79 | 53342.3 | 2846 |
| 2026-03-26T05:00:00+00:00 | 53342.3 | 53407.3 | 53092.79 | 53217.79 | 4805 |
| 2026-03-26T06:00:00+00:00 | 53217.79 | 53497.3 | 53147.31 | 53472.31 | 3904 |
| 2026-03-26T07:00:00+00:00 | 53472.31 | 53479.81 | 53177.8 | 53347.29 | 1369 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T16:00:00+00:00 | 66425.01 | 66782.5 | 66397.99 | 66585 | 7203 |
| 2026-09-25T17:00:00+00:00 | 66585 | 66662.51 | 66550 | 66595 | 2401 |
| 2026-09-25T18:00:00+00:00 | 66595 | 66692.49 | 66577.49 | 66600.01 | 1659 |
| 2026-09-25T19:00:00+00:00 | 66600.01 | 66767.49 | 66570.01 | 66702.49 | 2203 |
| 2026-09-25T20:00:00+00:00 | 66702.49 | 66725 | 66648.01 | 66688 | 364 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('JPN225_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('JPN225_1h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

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

df = pd.read_csv('JPN225_1h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1h')
print(pf.stats())
```

## Download full data

The complete **JPN225** archive on **[getdata.finance](https://getdata.finance/datasets/jpn225)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **98,600** rows at `1h`, plus all other timeframes in the same ZIP.

**[-> Get the full JPN225 dataset on getdata.finance](https://getdata.finance/datasets/jpn225)**

---
*GetData · JPN225 1h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/jpn225)*
