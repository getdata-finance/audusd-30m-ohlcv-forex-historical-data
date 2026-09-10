# AUDUSD 30m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-175_921_rows-blue)](https://getdata.finance/datasets/audusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/audusd)

### -> [**Download the full AUDUSD dataset on getdata.finance**](https://getdata.finance/datasets/audusd)

**AUDUSD 30m OHLCV forex historical data** — ultra high-quality 30m OHLCV for **Australian Dollar / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **Australian Dollar / US Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/audusd) · **175,921** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `AUDUSD_30m.csv` (6,255 rows, `2026-03-10` -> `2026-09-09`, 646.33 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/audusd)** — **175,921** `30m` rows (full `1m`: 5,263,475), **11 timeframes**, `2012-06-24` -> `2026-09-09`.

## Download sample

**[AUDUSD_30m.csv](https://github.com/getdata-finance/audusd-30m-ohlcv-forex-historical-data/blob/main/AUDUSD_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/audusd-30m-ohlcv-forex-historical-data/main/AUDUSD_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/audusd-30m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/audusd-30m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/audusd-30m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/audusd](https://getdata.finance/datasets/audusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/audusd))** |
|---|--:|---|
| Instrument | Australian Dollar / US Dollar · Forex | Australian Dollar / US Dollar · Forex |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 30m rows | 6,255 | **175,921** |
| Size | 646.33 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/audusd) |
| Period | `2026-03-10` -> `2026-09-09` | `2012-06-24` -> `2026-09-09` |
| File | `AUDUSD_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/audusd) |
| Coverage report | — | [AUDUSD coverage](https://getdata.finance/coverage/audusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/audusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/audusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUDUSD_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T19:00:00+00:00 | 0.73612 | 0.7364 | 0.73514 | 0.73521 | 12164 |
| 2026-03-10T19:30:00+00:00 | 0.73521 | 0.7355 | 0.73438 | 0.73477 | 13360 |
| 2026-03-10T20:00:00+00:00 | 0.73477 | 0.7351 | 0.73432 | 0.73483 | 3400 |
| 2026-03-10T20:30:00+00:00 | 0.73483 | 0.73484 | 0.73448 | 0.73474 | 1861 |
| 2026-03-10T21:00:00+00:00 | 0.73474 | 0.73493 | 0.73436 | 0.7346 | 402.97968 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T00:00:00+00:00 | 0.72208 | 0.7226 | 0.72208 | 0.72245 | 3375 |
| 2026-09-09T00:30:00+00:00 | 0.72245 | 0.72267 | 0.72222 | 0.72261 | 2755 |
| 2026-09-09T01:00:00+00:00 | 0.72261 | 0.72261 | 0.72215 | 0.72228 | 3149 |
| 2026-09-09T01:30:00+00:00 | 0.72228 | 0.7225 | 0.72195 | 0.72231 | 2648 |
| 2026-09-09T02:00:00+00:00 | 0.72231 | 0.72232 | 0.72219 | 0.72219 | 257 |

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

df = pd.read_csv('AUDUSD_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUDUSD_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AUDUSD_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **AUDUSD** archive on **[getdata.finance](https://getdata.finance/datasets/audusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **175,921** rows at `30m`, plus all other timeframes in the same ZIP.

**[-> Get the full AUDUSD dataset on getdata.finance](https://getdata.finance/datasets/audusd)**

---
*GetData · AUDUSD 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/audusd)*
