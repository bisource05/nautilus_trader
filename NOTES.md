# Notes on this fork

- Upstream: https://github.com/nautechsystems/nautilus_trader
- Fork: https://github.com/bisource05/nautilus_trader
- Source that led me here: https://x.com/carm1nee/article/2113257064352915664 ("The 10 Most Dangerous GitHub Repos in Trading", Carm1ne, Oct 22, 2026)
- Role in that stack: Execution desk - trading engine

## What it is

A Rust-native, event-driven trading engine where the same strategy code runs in backtest and in live trading, with backtests resolving down to the nanosecond, across crypto, FX, equities, futures, options and prediction markets.

## Caution

Prototype elsewhere and port only what survives. Live trading adds venue, timing and reconciliation effects a backtest cannot fully reproduce, and the v2 release covered here was still a release candidate not recommended for real capital.

## Status

Forked Oct 27, 2026. Nothing here has been run, configured, or connected to any account, API key, or real money. Paper / dry-run first, and only after a walk-forward backtest with fees, a look-ahead check, and 30 days on paper.
