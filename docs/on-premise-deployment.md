# Reviewing an on-premise proposal

## Input and scope

Ask for a versioned proposal showing local components, dependencies, resources, data paths and responsibilities. This page does not provide a Kurogane Hub installation procedure.

## Questions to resolve

- Which systems must remain available for the service to work: identity, DNS, time, storage or external licensing?
- Who patches the host and application, and how is rollback tested?
- Where are backups stored, who can decrypt them, and when was a restore demonstrated?
- What support access exists, how is it approved and how is it revoked?
- What logs are available when the application or host is unavailable?

## Evidence exercise

In an agreed isolated environment, restore a known synthetic dataset to a replacement host. Verify version, access restrictions, retained data and operation after restart. Capture elapsed recovery time and lost-data interval; do not assume they meet a target until compared with an agreed requirement.

## Output

An acceptance record linking each question to dated evidence or an unresolved item. Keep topology and recovery secrets private. Local hosting alone does not prove isolation, resilience or compliance. Use [data-control questions](data-sovereignty.md) for backups and support paths.
