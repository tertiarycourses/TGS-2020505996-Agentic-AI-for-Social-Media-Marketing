# Lab 6: Build a Listening and Anomaly Triage Agent

**Mappings:** LO3 · A3 · K8 · K10

## Scenario

Detect a CPL spike and rising negative feedback without allowing the agent to pause live campaigns automatically.

## What you will produce

alerts.csv and incident_triage.md

## Tools

Spreadsheet editor · text editor · optional approved AI assistant

## Mock data supplied

- `mock_data/daily_signals.csv`
- `mock_data/alert_rules.csv`
- `mock_data/evidence_preview.csv`

## Detailed procedure

1. Calculate a rolling baseline for each signal.
2. Apply the provided threshold rules.
3. Join contextual events before assigning likely cause.
4. Create an alert with evidence, severity and owner.
5. Propose a reversible action and rollback condition.
6. Record that a human—not the agent—decides whether to pause.

## Verification

- [ ] The 2026-09-05 CPL and comment alerts fire.
- [ ] The budget increase is retained as context.
- [ ] No rule authorizes automatic campaign pause.
- [ ] The alert includes source rows and owner.

## Troubleshooting

- If every day alerts, compare against a stable baseline and tune severity.
- If no alert fires, check numeric types and operators.

## Cleanup

- Delete test alerts marked as real incidents.
- Retain the rules, mock data and final triage record.

## Safety and privacy

Use only the supplied mock data. Do not paste live customer records, credentials, access tokens, or unpublished campaign data into any AI tool.
