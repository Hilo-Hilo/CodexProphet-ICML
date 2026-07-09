# Artifact Manifest

Generated: 2026-07-09

## Data

| Path | Description |
|---|---|
| `data/prophet-arena-raw/dr_strange_eval_2026-06-14.csv` | Official hackathon result export. |
| `data/forward-eval-cleaned/master_rows.csv` | Cleaned forward-eval event-level rows. |
| `data/forward-eval-cleaned/paired_scores.csv` | Cleaned paired score ledger. |
| `data/forward-eval-cleaned-exclude-nointerest/master_rows.csv` | Event-level rows excluding no-interest markets. |
| `data/forward-eval-cleaned-exclude-nointerest/paired_scores.csv` | Paired score ledger excluding no-interest markets. |
| `findings/forward-eval-findings/data/master_per_label.csv` | Main public label-level analysis table. |
| `findings/forward-eval-findings/data/master_rows.csv` | Public event-level analysis table. |
| `findings/forward-eval-findings/data/per_event_summary.csv` | Per-event summary table. |

## Generated Results

| Path | Description |
|---|---|
| `analysis/eval-results/results_table.csv` | Headline score/result table. |
| `analysis/normalized-brier/summary_stats_normalized.json` | Normalized Brier aggregate statistics. |
| `analysis/normalized-brier/category_normalized_brier_significance.csv` | Category-level normalized Brier summary. |
| `analysis/normalized-brier/event_type_normalized_brier_summary.csv` | Event-type normalized Brier summary. |
| `analysis/normalized-brier/random_baseline_brier_sanity.csv` | Random-baseline sanity table. |

## Diagrams And Charts

| Path | Description |
|---|---|
| `analysis/normalized-brier/*.png` | Normalized Brier plots. |
| `findings/forward-eval-findings/figures-updated-jul05/*.png` | Final forward-eval figures. |
| `analysis/visual-assets/*.png`, `analysis/visual-assets/*.svg` | Generated visual diagrams and Nano Banana assets. |
| `analysis/presentation-charts/*.png` | Final presentation charts/contact sheets. |

## Explicitly Excluded

This repo intentionally does not include:

- Source code for the forecasting system.
- Runtime variant source snapshots.
- Prompt text, method prompts, or prompt templates.
- Skills or agent setup.
- Raw trace logs, API prediction logs, request workspaces, local paths, or secrets.
- Trading/backtest findings.
