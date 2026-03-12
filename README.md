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
| Universe Construction | Final run done; Done |
| Data Processing | Final run done; Done |
| Statistical Analysis | Final run done; Done |
| LOB Simulator & Comparison Engine | Write-up in progress |
| Baseline Strategy | Done |
| Markov Filter | Write-up in progress |
| Risk Management | Text near-final |
| Walk-Forward Framework (EG test, AR(1) / half-life, Bayesian optimisation w/ blocked CV) | Write-up in progress |
| Overfitting Analysis | Not started on text |
| Results | Pending (final runs outstanding) |
| Conclusion | Not started |

The current [(`draft`)](draft.pdf) contains the near-final sections of the paper.
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
