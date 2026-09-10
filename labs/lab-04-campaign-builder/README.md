# Lab 4: Assemble a Governed Campaign Package

**Mappings:** LO1 · LO2 · A1 · A2 · K3 · K4 · K8

## Scenario

Translate approved content briefs into a campaign/ad-set/ad package without publishing to a live account.

## What you will produce

campaign_package.json and approval_log.csv

## Tools

JSON editor · spreadsheet editor · mock Ads Manager worksheet

## Mock data supplied

- `mock_data/audience_segments.csv`
- `mock_data/creative_inventory.csv`
- `mock_data/evidence_preview.csv`

## Detailed procedure

1. Create a campaign object with one outcome objective.
2. Create ad sets with audience, budget, schedule and suppression fields.
3. Attach only approved creative with valid usage rights.
4. Add a preflight checklist for destination, tracking and naming.
5. Record a human approval decision with reason and reviewer role.
6. Export a package for simulation only; do not publish.

## Verification

- [ ] Campaign, ad set and ad fields are at the correct hierarchy.
- [ ] Daily budget stays within SGD 250.
- [ ] Pending CR-03 is blocked.
- [ ] The package contains no live credential or account ID.

## Troubleshooting

- If delivery settings conflict, trace which hierarchy owns the field.
- If a creative is blocked, check status and rights_expiry.

## Cleanup

- Delete any accidental real account identifiers.
- Keep the approved simulation package and decision log.

## Safety and privacy

Use only the supplied mock data. Do not paste live customer records, credentials, access tokens, or unpublished campaign data into any AI tool.
