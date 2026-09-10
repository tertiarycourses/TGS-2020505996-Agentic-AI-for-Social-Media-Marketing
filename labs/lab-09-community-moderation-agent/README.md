# Lab 9: Triage Community Messages with Human Oversight

**Mappings:** LO5 · A5 · K5 · K9 · K10

## Scenario

Classify and route a queue of comments while protecting personal data and preserving legitimate criticism.

## What you will produce

moderation_queue.csv and response_log.md

## Tools

Spreadsheet editor · policy rubric · optional approved AI assistant

## Mock data supplied

- `mock_data/community_messages.csv`
- `mock_data/moderation_policy.csv`
- `mock_data/evidence_preview.csv`

## Detailed procedure

1. Redact personal identifiers before AI-assisted classification.
2. Assign intent, sentiment, severity and confidence.
3. Apply the policy ladder: allow, assist, review, escalate or remove.
4. Draft responses only for low-risk items.
5. Capture evidence and reason codes for sensitive decisions.
6. Review a sample for false positives and local-language errors.

## Verification

- [ ] Order number in M002 is redacted before processing.
- [ ] M004 is emergency-escalated and not auto-replied.
- [ ] M003 remains visible while routed for human review.
- [ ] Every decision has a reason code.

## Troubleshooting

- If sarcasm or dialect is uncertain, lower confidence and route to review.
- If criticism is removed merely for being negative, revisit the policy criterion.

## Cleanup

- Delete unredacted scratch copies.
- Retain only the redacted queue and evidence log.

## Safety and privacy

Use only the supplied mock data. Do not paste live customer records, credentials, access tokens, or unpublished campaign data into any AI tool.
