# Satellite integration boundaries

A satellite is a conceptual component near a data source that maps observations into events. The public repositories supply a local contract and synthetic examples; they do not establish a deployed satellite architecture.

## Public exercise

1. Choose invented asset, alarm and telemetry records.
2. Map them to the [SDK contract](https://github.com/Mysthrala-Kurogane-Defense-Labs/kurogane-satellite-sdk/blob/main/docs/event-contracts.md).
3. Validate their types and timestamps locally.
4. Run [Labs](https://github.com/Mysthrala-Kurogane-Defense-Labs/kurogane-labs) and compare expected event counts and gaps.

The SDK only previews publication. It does not implement receiver authentication, HTTP delivery, buffering, retries or a Hub API.

## Decisions for a real integration

Ask for protocol and version, read-only source permissions, asset mapping, clock reliability, credentials, throughput limits, data minimization, failure policy and receiver acknowledgment behavior. Specify where trust changes between source, connector, receiver and operator. A valid schema is not source authentication.

## Output

A mapping table, validated synthetic fixtures and a list of unanswered transport decisions. Private-core interoperability remains unverified until an agreed versioned receiver contract and actual integration test are available.
