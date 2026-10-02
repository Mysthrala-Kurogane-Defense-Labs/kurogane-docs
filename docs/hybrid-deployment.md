# Reviewing a hybrid proposal

## Input

Draw the proposed local and remote components and classify every transferred field. Include logs, telemetry, backups, support sessions and identity dependencies. No supported private Hub hybrid deployment is established by this guide.

## Review steps

1. Specify permitted destinations, protocols, identities, retention and data minimization.
2. Define behavior during lost connectivity: what continues locally, what queues, storage limits and what is dropped.
3. Define reconnection behavior: duplicate handling, order, expired credentials and operator visibility.
4. Assign owners for both sides, including incident notification and remote-service changes.

## Test before accepting

Use synthetic data in an isolated environment. Interrupt connectivity under an approved test plan, observe local behavior, restore the connection and compare delivered IDs with the original set. Check duplicate and missing-event handling. A network outage must not silently become a claim that there were no alarms.

## Output and limit

Retain the flow inventory, tested outage behavior and unresolved dependencies. The public SDK has no network transport or persistent queue. The public lab only models missing observations and cannot validate this deployment's availability. See [data control](data-sovereignty.md).
