# CodexProfit ICML Artifact Bundle

Public artifact bundle for the ICML presentation.

This repository contains generated evaluation results, data tables, diagrams, and Nano Banana / Paper Banana presentation charts. It intentionally does not include production forecasting source code, runtime setup, prompt text, skills, request workspaces, traces, logs, or variant source folders.

## Contents

| Path | Contents |
|---|---|
| `data/prophet-arena-raw/` | Official hackathon evaluation CSV used for reported score analysis. |
| `data/forward-eval-cleaned/` | Cleaned forward-eval event-level score tables. |
| `data/forward-eval-cleaned-exclude-nointerest/` | Cleaned forward-eval tables with no-interest markets excluded. |
| `findings/forward-eval-findings/data/` | Public derived analysis tables. |
| `findings/forward-eval-findings/figures-updated-jul05/` | Final forward-eval figures used in the presentation. |
| `analysis/eval-results/` | Generated headline result table. |
| `analysis/normalized-brier/` | Normalized Brier summary tables and charts. |
| `analysis/visual-assets/` | Generated system diagrams and Nano Banana visual assets. |
| `analysis/presentation-charts/` | Final generated presentation charts/contact sheets. |
| `docs/ARTIFACT_MANIFEST.md` | File-level summary and exclusion notes. |

## Exclusions

The public repo deliberately excludes:

- Forecasting service source code.
- Runtime variant source folders.
- Prompt templates and method prompts.
- Skills and agent setup.
- Raw traces, request workspaces, private logs, and API service configuration.
- Trading/backtest findings.

## Notes

Some CSVs contain model/variant identifiers used for result grouping. They are data labels only; no runtime implementation or prompt content is included.
