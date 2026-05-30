# Handoff Rules

A charter should not be the end of the workflow. When it creates downstream
work, produce a concise handoff note.

## Handoff note format

Source module: Project Charter Initiation Agent
Recommended next module or human owner:
Work item:
Lifecycle stage:

Confirmed facts:
Assumptions:
Evidence gaps:
Decisions needed:
Risks, dependencies, or actions:
Do not pass downstream:
Suggested first prompt:

## Common handoffs

| Condition | Handoff target | Pass downstream |
|---|---|---|
| Approved charter needs portfolio comparison | Portfolio Prioritization Scoring Agent | Initiative ID/name, sponsor, owner, business outcome, scope, expected value, cost/capacity estimate, risks, dependencies, mandatory status |
| Approved charter needs sequencing | Portfolio Capacity Sequencing Planner | Milestones, capacity needs, fixed windows, dependencies, constraints, shared teams, risk dates |
| Project moves into governed execution | PMO Governance Operations Log | Governance rhythm, decision log needs, action register seeds, risks, dependencies, open decisions, escalation path |
| Release, validation, UAT, or launch gate is visible | Release Readiness and UAT Governance Pack | Scope, deliverables, acceptance criteria, environments/data needs, milestone targets, signoff owners, known blockers |
| Charter contains value claims | Value Realization Governance Ledger | Expected benefits, metrics, baselines, targets, owners, timing, evidence limits |
| Control or exposure risk is material | Controls Exposure Governance Toolkit | Exposure description, owner, impacted process/system/vendor, evidence, remediation dependency, open authority question |

## Route upstream when

| Input pattern | Better route |
|---|---|
| Idea lacks sponsor, outcome, scope, or decision need | Portfolio Intake Readiness Triage System or Business Case System |
| Investment logic is not yet defensible | Business Case System |
| AI idea needs proof, build/buy/wait routing, or workflow-shape review | AI Opportunity Intelligence Review System |
| Existing AI artifact needs reliance/risk classification | AI Artifact Lifecycle Governance System |

## Do not pass downstream

- Draft scope that the sponsor has not confirmed.
- Assumptions as if they are approved constraints.
- Sensitive source artifacts that are not needed for the receiving workflow.
- Detailed schedules, backlogs, or solution designs unless the receiving module explicitly needs them.
