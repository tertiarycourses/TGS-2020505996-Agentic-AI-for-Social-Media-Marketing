# Lab 7: Evaluate an A/B Test and Budget Decision

**Mappings:** LO4 · A4 · K7

## Scenario

Determine whether creative B should receive more budget without reacting to an early, unstable result.

## What you will produce

experiment_decision.md and budget_change.json

## Tools

Spreadsheet editor · calculator · optional approved AI assistant

## Mock data supplied

- `mock_data/experiment_results.csv`
- `mock_data/decision_policy.csv`
- `mock_data/evidence_preview.csv`

## Detailed procedure

1. Confirm only the creative variable differs.
2. Compute CTR, CVR, CPL and relative lift for both cells.
3. Compare sample size to the precommitted rule.
4. Evaluate business significance and uncertainty.
5. Propose ship, extend or stop with rationale.
6. If shipping, create a bounded budget change and rollback rule.

## Verification

- [ ] Both cells exceed 500 clicks.
- [ ] Relative CVR lift is calculated from the control baseline.
- [ ] Budget change does not exceed 15%.
- [ ] The decision states evidence and uncertainty.

## Troubleshooting

- If the lift looks huge, verify percentages use the correct denominator.
- If the test changed multiple variables, mark the causal conclusion invalid.

## Cleanup

- Remove exploratory metrics chosen after the result.
- Retain the precommitted policy and final decision.

## Safety and privacy

Use only the supplied mock data. Do not paste live customer records, credentials, access tokens, or unpublished campaign data into any AI tool.
