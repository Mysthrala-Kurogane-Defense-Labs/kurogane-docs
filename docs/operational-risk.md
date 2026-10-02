# Prioritizing operational risk

## Input

Choose the bounded workflow from [onboarding](sme-onboarding.md). Identify what a loss of availability, incorrect information or unauthorized change would affect: people, equipment, delivery, quality and recovery.

## Record a scenario

| Field | Synthetic example |
| --- | --- |
| Dependency and owner | Engineering workstation; maintenance lead |
| Failure or misuse | Support account remains enabled after service |
| Consequence to validate | Unauthorized change could interrupt the line |
| Existing evidence | Account list exists; approval history unknown |
| Next action | Review support accounts with owner and provider |
| Completion evidence | Dated review and tested revocation |

## Prioritize

Discuss consequence and uncertainty with the operational owner. Prefer resolving a critical unknown to assigning a precise-looking score without data. Record existing controls, evidence age and recovery dependence. Assign an action owner and review date.

## Output and limit

Keep a short action register linked to evidence. A security observation is not a validated safety consequence, and correlation between an alarm and downtime is not causality. This exercise supports prioritization; it does not replace process-safety engineering or certify risk reduction. [NIST OT guidance](references.md) supplies broader context.
