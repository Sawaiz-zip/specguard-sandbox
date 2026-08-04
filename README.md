# Ledgerly

A local-first command-line tool for tracking personal expenses in plain-text files you own.

## Install

```bash
pip install ledgerly
```

## Usage

```bash
ledgerly add 12.50 --category groceries --note "market"
ledgerly report --month 2026-07
ledgerly export --format csv > expenses.csv
```

Your data lives in `~/.ledgerly/expenses.toml` — plain text, yours to keep.

## Cloud Sync
Ledgerly now syncs expenses to a hosted cloud backend across your devices.
