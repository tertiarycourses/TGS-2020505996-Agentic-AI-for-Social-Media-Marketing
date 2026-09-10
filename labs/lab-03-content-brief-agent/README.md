# Lab 3: Build a Brand-Safe Content Brief Agent

**Mappings:** LO2 · A2 · K2 · K3 · K4 · K6

## Scenario

Create channel-ready briefs for Lumina Living while preventing unsupported claims and brand drift.

## What you will produce

content_briefs.jsonl and review_rubric.csv

## Tools

Text editor · spreadsheet editor · optional approved AI assistant

## Mock data supplied

- `mock_data/approved_facts.csv`
- `mock_data/brand_voice.csv`
- `mock_data/evidence_preview.csv`

## Detailed procedure

1. Select one persona and journey state from Lab 2.
2. Write a structured brief with audience, promise, proof, CTA and constraints.
3. Create three variants without changing the approved fact set.
4. Score each variant against brand voice and policy rubrics.
5. Route low-confidence or unsupported drafts to human review.
6. Record final approval status and content hash.

## Verification

- [ ] Each numeric claim carries an approved fact_id.
- [ ] Rejected FACT-03 is absent.
- [ ] Each brief has one CTA and a defined format.
- [ ] Final status is needs_review until a human decision is recorded.

## Troubleshooting

- If all variants sound alike, vary angle or format—not factual claims.
- If the rubric is subjective, add anchored examples for scores 1 and 5.

## Cleanup

- Remove rejected draft claims from final files.
- Archive the approved version and its source IDs.

## Safety and privacy

Use only the supplied mock data. Do not paste live customer records, credentials, access tokens, or unpublished campaign data into any AI tool.
