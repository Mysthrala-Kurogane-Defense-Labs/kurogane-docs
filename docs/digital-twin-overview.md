# Asset model and digital twin terminology

The public examples contain an asset inventory and invented events. They do not demonstrate a synchronized representation of a physical plant and should be described as a **synthetic asset model**.

## Questions before using a stronger claim

- Which physical system and operating conditions are represented?
- Which approved sources update the model, at what intervals and with what quality limits?
- How are stale, missing or contradictory observations identified?
- What behavior is modeled and independently validated?
- What decisions may use the model, and who accepts its limitations?

## Practical output

Start with the [asset register](plant-modeling.md). For every proposed model capability, record the source, validation method, timestamp policy and unresolved limitations. Separate a diagram, an inventory, live telemetry and a validated process model in descriptions.

The Python lab is deterministic and fixed; it is not a physics simulator or a real-time replica. Running it provides no evidence about a physical asset's safety or performance.
