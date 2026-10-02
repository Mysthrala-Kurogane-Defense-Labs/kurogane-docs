# Choosing a deployment model

This is a provider-evaluation guide. No installer or supported private Hub topology is published here.

## Inputs

List required data, outage tolerance, support responsibility, connectivity limits, retention needs and constraints on transfers. Confirm these with operations and IT before comparing products.

| Question | On-premise | Hybrid |
| --- | --- | --- |
| Who operates the local host? | Named local or contracted owner | Still needs a local owner |
| What happens without Internet? | Test local dependencies | Test local buffering and deferred processing |
| Where can data leave the site? | Inventory updates, support and backups too | Document each external flow |
| Who restores service? | Local restore procedure and evidence | Local plus remote-component recovery |
| What evidence is needed? | Version, access review, restore test | Same plus transfer and remote-service evidence |

## Decision steps

1. Draw proposed components and data flows without secrets.
2. Assign responsibility for identity, updates, backups, monitoring and incident response.
3. Ask the provider to demonstrate outage, restart, restore and access revocation in a separate test environment.
4. Record unresolved assumptions and the consequence of each failure.

## Output

A selected model with reasons, named owners, required evidence and acceptance criteria. Hosting locally does not by itself establish security or data sovereignty. Follow [on-premise](on-premise-deployment.md) or [hybrid](hybrid-deployment.md) questions before procurement.
