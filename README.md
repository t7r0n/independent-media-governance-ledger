# Independent Media Governance Ledger

A governance ledger for media portfolios that tracks editorial policy versions, ownership/brand relationships, infrastructure dependencies, and public corrections as verifiable timelines.

## Why This Exists

independent media operators need durable governance and provenance systems that prove editorial independence, ownership, and platform resilience over time.

## What It Builds

- Replays synthetic `independent` and `media` cases against the project's evidence rules.
- Scores `independent_coverage`, `media_risk`, and `operators_precision` so regressions are visible in CSV and JSON.
- Plants `independent drift` and `media gap` failures as negative controls.
- Writes citation-locked decision claims; unsupported claims fail verification.
- Exports a review dashboard and demo pack for `independent-media-governance-ledger` without hosted services.

## Local Run

```bash
uv sync
uv run independent-media-governance-ledger all
uv run pytest -q
uv run ruff check .
```

## Outputs

- `outputs/analysis.json`
- `outputs/scenario_report.csv`
- `outputs/decision_report.md`
- `outputs/evidence_packet.md`
- `outputs/domain_rubric.json`
- `outputs/failure_matrix.md`
- `outputs/trace_graph.mmd`
- `outputs/dashboard.html`
- `outputs/demo_pack.zip`

## Sources

- https://w-worldmedia.com/about/

## Boundary

This repository uses synthetic fixtures only. It has no credentials, no customer data, no outreach data, and no dependency on a hosted API.
