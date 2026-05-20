# Independent Media Governance Ledger

A governance ledger for media portfolios that tracks editorial policy versions, ownership/brand relationships, infrastructure dependencies, and public corrections as verifiable timelines.

![Independent Media Governance Ledger working dashboard](outputs/project_working.svg)

## Why it exists

independent media operators need durable governance and provenance systems that prove editorial independence, ownership, and platform resilience over time.

Most internal demos stop at a pretty chart. This repository is built around the harder part: a repeatable path from fixture, to failure, to evidence, to the operator action a serious team would actually trust.

## What is inside

- A deterministic replay harness tuned around independent, media, and operators.
- Company-specific strategy code in `src/independent_media_governance_ledger/strategy.py`, not just README-level customization.
- Citation-locked reports where every decision claim has to point back to a generated evidence ID.
- Two visual artifacts generated from the latest run: `outputs/project_working.svg` and `outputs/evidence_map.svg`.
- A portable demo pack with JSON, CSV, Markdown, HTML, SVG, and benchmark artifacts.

![Independent Media Governance Ledger evidence map](outputs/evidence_map.svg)

## Signals it measures

- `independent coverage`
- `media risk`
- `operators precision`
- `durable latency`

## Failure modes it plants

- independent drift
- media gap
- operators misroute
- durable blindspot

## Run it locally

```bash
uv sync
uv run independent-media-governance-ledger all
uv run pytest -q
uv run ruff check .
```

## Outputs worth opening

- `outputs/dashboard.html`
- `outputs/project_working.svg`
- `outputs/evidence_map.svg`
- `outputs/operator_brief.md`
- `outputs/decision_report.md`
- `outputs/strategy_model.json`
- `outputs/demo_pack.zip`

## Sources

- https://w-worldmedia.com/about/

## Boundary

Everything runs locally against synthetic fixtures. There are no credentials, no customer records, no outreach files, and no hosted API dependency.
