# Markov-Filtered Mean Reversion on US Equities — Working Paper

Empirical study of whether a Markov-based spread-state filter can improve
entry selection in equity pairs trading, under free-data constraints and
realistic execution assumptions.

This repository contains the current draft and final pipeline runs.
The accompanying code is maintained separately at [Mean-Reversion-Projekt](https://github.com/NiklasFrac/Mean-Reversion-Projekt).

---

## Status

This is a working paper. The table below reflects the current state.

| Section | Status |
|---|---|
| Universe Construction | Final run done; text near-final |
| Data Processing | Final run done; text near-final |
| Statistical Analysis | Final run done; text near-final |
| Baseline Strategy | Text near-final |
| Markov Filter | Text near-final |
| Risk Management | Text near-final |
| Walk-Forward Framework (EG test, AR(1) / half-life, Bayesian optimisation w/ blocked CV) | Write-up in progress |
| LOB Simulator & Comparison Engine | Write-up in progress|
| Overfitting Analysis | Not started on text |
| Results | Pending (final runs outstanding) |
| Conclusion | Not started |

The current draft (`draft`) reflects the near-final sections.
Sections not yet written are absent rather than placeholder-filled.

---

## Runs

Final outputs for completed stages are stored in the corresponding folders in this repository.

---

## Methodological stance

The paper is written with explicit limitations in scope:
- Daily OHLCV data only (no tick data)
- Free data sources; results are conditioned on this constraint
- No claims of live tradability; the goal is rigorous empirical analysis under clearly stated assumptions
