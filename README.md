# Markov-Filtered Mean Reversion on US Equities

This repository contains the research draft and exported artifacts for an empirical study on mean-reversion in US equity pairs under free-data constraints.

The project examines whether a finite-state Markov approximation of the rolling spread Z-score can improve entry selection relative to a baseline daily-bar pairs-trading strategy. The emphasis is on transparent empirical design, split-consistent evaluation, and reproducible research artifacts.

## Repository contents

This repository contains:

- the current working paper draft in LaTeX,
- the compiled PDF draft,
- exported run artifacts for completed pipeline stages,
- supporting materials for the empirical write-up.

The implementation codebase is maintained separately in the corresponding code repository.

## Quick links

- [Current PDF draft](draft.pdf)
- [LaTeX source](draft.tex)
- [Code repository](https://github.com/NiklasFrac/Mean-Reversion-Projekt)

## Project scope

The study is designed as a reproducible empirical investigation of a constrained statistical-arbitrage setting on US equities. In particular, it separates

- global pair selection from downstream backtesting,
- split-specific calibration from out-of-sample evaluation,
- baseline strategy logic from the Markov-based entry overlay,
- research claims from broader live-trading claims.

The intended contribution is therefore methodological and empirical: the project studies whether the proposed overlay improves trade selection within a transparent daily-data framework.

## Repository structure

- `draft.tex`: current LaTeX paper source  
- `draft.pdf`: compiled draft PDF  
- `ANL-...`: analysis-stage exported artifacts  
- `PRC-...`: processing-stage exported artifacts  
- `RUN-...`: universe-level exported artifacts
- `README.md`: repository overview  

The exported folders are retained as research artifacts corresponding to completed stages of the pipeline.

## Current status

The repository is maintained as an active working-paper and artifact repository. Core methodological sections are already drafted, while some later sections remain in progress.

| Section | Status |
|---|---|
| Universe Construction | Done |
| Data Processing | Done |
| Statistical Analysis | Done |
| Baseline Strategy | Done |
| Markov Filter | Write-up in progress |
| Risk Management | Text near-final |
| Walk-Forward Framework | Write-up in progress |
| LOB Simulator & Comparison Engine | Write-up in progress |
| Overfitting Analysis | Not started on text |
| Results | Pending |
| Conclusion | Not started |

## Reading guide

For a first pass, the recommended order is:

1. read the current PDF draft,
2. consult the status table for section maturity,
3. inspect the exported run artifacts for completed stages,
4. refer to the linked code repository for implementation details.

## Notes

The current draft already covers the core research framing, universe and data construction, processing pipeline, statistical selection framework, and formal strategy specification. The remaining work is focused primarily on completing the later write-up sections, consolidating the final empirical results, and sharpening the concluding discussion
