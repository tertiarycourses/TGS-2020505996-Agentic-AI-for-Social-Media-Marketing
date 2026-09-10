# Lab 8: Orchestrate an Approval-Aware Content Calendar

**Mappings:** LO4 · A4 · K4 · K8

## Scenario

Schedule an eight-item campaign calendar with timezones, dependencies, rights expiry and idempotent publishing requests.

## What you will produce

approved_calendar.csv and exception_queue.csv

## Tools

Spreadsheet editor · calendar template · optional approved AI assistant

## Mock data supplied

- `mock_data/content_backlog.csv`
- `mock_data/calendar_slots.csv`
- `mock_data/evidence_preview.csv`

## Detailed procedure

1. Validate each item status and validity window.
2. Match approved assets to compatible slots and formats.
3. Resolve dependencies before scheduling.
4. Create a deterministic publish request_id.
5. Route blocked items to an exception queue.
6. Reconcile the planned schedule with mock actual post IDs.

## Verification

- [ ] Pending CNT-103 is not scheduled.
- [ ] All timestamps include +08:00.
- [ ] No content is scheduled after valid_to.
- [ ] Every scheduled row has a unique request_id.

## Troubleshooting

- If a duplicate appears, check request_id construction.
- If a slot is empty, inspect approval, rights and format constraints.

## Cleanup

- Remove any live webhook or platform credentials.
- Retain the final calendar and exception queue.

## Safety and privacy

Use only the supplied mock data. Do not paste live customer records, credentials, access tokens, or unpublished campaign data into any AI tool.
