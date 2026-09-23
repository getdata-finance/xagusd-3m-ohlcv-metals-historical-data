# XAGUSD 3m OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_011_168_rows-blue)](https://getdata.finance/datasets/xagusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xagusd)

### -> [**Download the full XAGUSD dataset on getdata.finance**](https://getdata.finance/datasets/xagusd)

**XAGUSD 3m OHLCV metals historical data** — ultra high-quality 3m OHLCV for **Silver / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **Silver / US Dollar** (Metals)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/xagusd) · **2,011,168** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `XAGUSD_3m.csv` (60,077 rows, `2026-03-23` -> `2026-09-23`, 5.43 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/xagusd)** — **2,011,168** `3m` rows (full `1m`: 5,671,224), **11 timeframes**, `2009-02-24` -> `2026-09-23`.

## Download sample

**[XAGUSD_3m.csv](https://github.com/getdata-finance/xagusd-3m-ohlcv-metals-historical-data/blob/main/XAGUSD_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xagusd-3m-ohlcv-metals-historical-data/main/XAGUSD_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/xagusd-3m-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xagusd-3m-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xagusd-3m-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xagusd](https://getdata.finance/datasets/xagusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xagusd))** |
|---|--:|---|
| Instrument | Silver / US Dollar · Metals | Silver / US Dollar · Metals |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 60,077 | **2,011,168** |
| Size | 5.43 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/xagusd) |
| Period | `2026-03-23` -> `2026-09-23` | `2009-02-24` -> `2026-09-23` |
| File | `XAGUSD_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xagusd) |
| Coverage report | — | [XAGUSD coverage](https://getdata.finance/coverage/xagusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xagusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/xagusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAGUSD_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T02:30:00+00:00 | 70.35 | 70.374 | 69.731 | 69.843 | 7628 |
| 2026-03-23T02:33:00+00:00 | 69.843 | 70.024 | 69.62 | 69.695 | 5764 |
| 2026-03-23T02:36:00+00:00 | 69.695 | 69.848 | 69.289 | 69.425 | 5784 |
| 2026-03-23T02:39:00+00:00 | 69.425 | 69.663 | 69.14 | 69.357 | 6219 |
| 2026-03-23T02:42:00+00:00 | 69.357 | 69.76 | 69.332 | 69.672 | 5548 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-23T01:48:00+00:00 | 66.605 | 66.636 | 66.567 | 66.617 | 1108 |
| 2026-09-23T01:51:00+00:00 | 66.617 | 66.642 | 66.507 | 66.512 | 1071 |
| 2026-09-23T01:54:00+00:00 | 66.512 | 66.512 | 66.387 | 66.419 | 1182 |
| 2026-09-23T01:57:00+00:00 | 66.419 | 66.477 | 66.41 | 66.46 | 919 |
| 2026-09-23T02:00:00+00:00 | 66.46 | 66.46 | 66.419 | 66.424 | 480 |

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

df = pd.read_csv('XAGUSD_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAGUSD_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('XAGUSD_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **XAGUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xagusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,011,168** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full XAGUSD dataset on getdata.finance](https://getdata.finance/datasets/xagusd)**

---
*GetData · XAGUSD 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xagusd)*
