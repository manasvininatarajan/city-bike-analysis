# city-bike-analysis

A data analysis report exploring how New Yorkers used Citi Bike through one of the city's coldest and snowiest months. Built as a portfolio project demonstrating end-to-end data work — from raw public data to a clean, shareable report.

**Includes:**
- Daily ridership across all 31 days with verified weather anomalies explained
- Commuter behavior analysis — hourly patterns, trip duration, peak times
- Rider mix breakdown — members vs. casual, e-bike vs. classic
- Top stations and most-traveled routes
- Minimal, chart-driven one-page report built without any charting libraries beyond Chart.js

**Live report:** https://manasvininatarajan.github.io/city-bike-analysis/

## Why I built this

I wanted to go from a raw public dataset to a polished, readable product — the kind of thing you'd actually hand to someone. Citi Bike publishes monthly trip data for free, and December 2025 turned out to be a genuinely interesting month: two snowstorms, the holidays, and 2.09 million rides despite all of it.

## Data source

Citi Bike System Data — publicly available at citibikenyc.com/system-data. Weather anomalies verified against NYC Emergency Management press releases and local news coverage.

## Tools

Python (standard library) · Chart.js · HTML/CSS

## Limitations

- **Single-month scope.** This analysis covers December 2025 only — a month shaped by holiday travel patterns and two snowstorms. Ridership behavior, peak times, and rider mix could look meaningfully different in a typical or warmer month, so findings here shouldn't be generalized to Citi Bike usage year-round without comparing against other months.
- **Weather verification relied on secondary sources.** Anomalies were cross-checked against NYC Emergency Management press releases and news coverage rather than raw meteorological station data, which is a reasonable proxy but not a precise dataset.
- **No year-over-year baseline.** Without comparing December data from prior years, it's hard to say how unusual this month's numbers actually were relative to typical December ridership.

*Data verified December 2025 — Citi Bike NYC, NYC Emergency Management*
