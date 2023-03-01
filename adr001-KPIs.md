# ADR 001: KPIs / Key Metrics Architecture

## Context

[Provide context for the decision, including any constraints or requirements that influenced the decision.]

## Decision

Time
- # Request per time unit (throughput)
- Percentiles -> latency
- sizing: Message PER API (throughput) -> vCore -> $$$
- #s average time per request

Quality
- % availability (time of availability of API) - AVG in General
- Used policies ( 00TB vs custom development )
- Reuse ( Architecture, source code)
- % Success vs Error

Cost/Budget
- Days invested to deliver the solution
- LoC (Lines of Code) -> Flow Mule, $$$$
- Used policies ( 00TB vs custom development )

## Status

[Indicate the current status of the decision, such as "proposed", "accepted", "rejected", "superseded", or "obsolete".]

## Consequences

[Describe the consequences, both positive and negative, of the decision, including any risks or dependencies.]

## Related documents

[List any related documents, such as requirements or design documents, that influenced the decision.]

### References
- https://github.com/joelparkerhenderson/architecture-decision-record
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/metrics-monitors-alerts/index.md
- https://github.com/pmerson/ADR-template
- https://github.com/joelparkerhenderson/architecture-decision-record/blob/main/examples/timestamp-format/index.md
- https://cloud.google.com/architecture/architecture-decision-records
