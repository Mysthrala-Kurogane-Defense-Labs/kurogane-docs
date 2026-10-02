# Plant inventory and dependencies

## Input

Use existing asset lists, owner interviews, vendor documentation and approved read-only records. Avoid unsolicited discovery traffic on operational networks.

## Build the register

Record asset ID, function, site/line, operational owner, maintenance owner, vendor/model, version when known, critical dependencies, access path, backup/recovery reference, source and last verification date. Store addresses and sensitive topology in a protected copy.

Use `unknown` for unverified values. A label on a drawing, a network observation and an owner interview are different evidence sources. Keep disagreements visible until resolved.

| Synthetic asset | Function / dependency | Owner | Evidence state |
| --- | --- | --- | --- |
| pump-1 | Fluid movement; depends on control-1 | Maintenance | Invented example only |
| workstation-1 | Engineering access to control-1 | OT lead | Version and restore test unknown |

## Validate the result

Ask the operational owner to confirm function and consequence of loss. Ask maintenance to confirm support and recovery information. Check that every critical dependency has an owner and that an asset ID is unique within its site.

## Output and limit

Retain a dated inventory and a list of unknowns with owners. This is an asset model, not automatically a digital twin, a complete network map or a proof of secure configuration. See [model terminology](digital-twin-overview.md) and [OT guidance sources](references.md).
