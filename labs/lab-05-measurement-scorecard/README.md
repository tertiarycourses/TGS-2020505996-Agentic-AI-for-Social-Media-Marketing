# Lab 5: Compute a Campaign Measurement Scorecard

**Mappings:** LO3 · A3 · K5 · K8

## Scenario

Reconcile a mock platform export and CRM outcome table, then calculate decision-ready metrics.

## What you will produce

scorecard.csv, metric_dictionary.md and funnel_analysis.md

## Tools

Spreadsheet editor · optional Python notebook

## Mock data supplied

- `mock_data/campaign_metrics.csv`
- `mock_data/crm_outcomes.csv`
- `mock_data/evidence_preview.csv`

## Detailed procedure

1. Validate required columns, types, currency and date window.
2. Calculate CTR, landing-action rate, CVR, CPL and ROAS.
3. Build a funnel showing counts and stage-to-stage rates.
4. Reconcile platform leads with CRM quality outcomes.
5. Write an evidence-linked interpretation with limitations.
6. Define scale, hold and stop decision rules.

## Verification

- [ ] CTR equals clicks divided by impressions.
- [ ] CPL equals spend divided by leads.
- [ ] ROAS is clearly labeled as revenue/ad spend.
- [ ] Every narrative claim cites a computed row.

## Troubleshooting

- If totals disagree, confirm the same campaign and date window.
- If a rate is unstable, show its raw count and avoid overclaiming.

## Cleanup

- Remove any formula scratch sheets with broken references.
- Retain the clean input, metric dictionary and scorecard.

## Safety and privacy

Use only the supplied mock data. Do not paste live customer records, credentials, access tokens, or unpublished campaign data into any AI tool.
