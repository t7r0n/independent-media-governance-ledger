# Failure Matrix: Independent Media Governance Ledger

| Scenario | Failure mode | Metric | Gate | Evidence |
| --- | --- | --- | --- | --- |
| independent evidence replay | independent_drift | independent_coverage | block release until cited evidence is regenerated | ev_0000 |
| durable operator packet | durable_blindspot | durable_latency | accept only if decision claims cite fixture evidence | ev_0007 |
| durable operator packet | durable_blindspot | durable_latency | accept only if decision claims cite fixture evidence | ev_0011 |
| operators regression harness | operators_misroute | operators_precision | open a regression issue with trace and benchmark delta | ev_0014 |
| media boundary probe | media_gap | media_risk | route to reviewer with evidence packet | ev_0021 |
| operators regression harness | operators_misroute | operators_precision | open a regression issue with trace and benchmark delta | ev_0022 |
| independent evidence replay | independent_drift | independent_coverage | block release until cited evidence is regenerated | ev_0028 |
