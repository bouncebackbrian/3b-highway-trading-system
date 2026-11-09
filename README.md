# 3B Highway Trading System

**Drive the markets like a pro driver, not a street racer.**

Educational trading framework, course materials, and a planned MetaTrader 5 Expert Advisor.

## Architecture

- **Core Trend Rider:** Daily EMA 20 / EMA 50 directional filter
- **Snapback Scalper:** M15 EMA 5 / EMA 13 / EMA 50 and RSI(5) W/M pattern signals
- **Safety Dispatcher:** Position sizing, drawdown protection, daily-loss halts, and demo-only beta gate

## Planned structure

- `01_Build_Docs/` — business plan, course, funnel, compliance, emails
- `02_Student_Downloads/` — approved student-facing worksheets and assets
- `03_Developer/` — EA requirements and eventual MQL5 source
- `ea-mt5/` — MT5 implementation (not yet developed)
- `tests/` — signal logic and risk manager tests

## Status

**Planning / pre-release.** No trading bot or paid course is deployed from this repository yet. Do not use any strategy with live capital based solely on these specifications.

## Safety

Trading has a substantial risk of loss. No returns or performance outcomes are guaranteed. A demo-only EA beta and independent testing are required before any live use.

## Publication

Course manuscripts, paid downloads, credentials, account identifiers, and proprietary EA source must not be committed to a public repository. Switch this repository to private before adding internal files.
