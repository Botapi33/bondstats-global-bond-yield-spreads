# Global Bond Yield Spreads

A live GitHub Pages dashboard for tracking sovereign bond yield spreads across countries using the BondStats global yield feed.

## What this tool does

This dashboard compares current government bond yields across countries against a selected benchmark.

It shows:

- benchmark yield
- widest positive spread
- tightest or negative spread
- average spread
- spread distribution chart
- country-by-country spread table
- region filtering
- benchmark switching
- live sorting options

## Why this version is better

The older BondStats spread page was more static and less transparent.

This GitHub version works directly from the live BondStats JSON feed and updates automatically.

## Spread logic

For each country:

Spread = country yield − benchmark yield

The benchmark can be changed live in the dashboard.

## Live data source

The dashboard reads from:

`https://botapi33.github.io/bondstats-global-yields/global_yields.json`

## Files

- `index.html`
- `README.md`
- `.nojekyll`

