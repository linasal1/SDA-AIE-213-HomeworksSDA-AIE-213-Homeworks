# Day 2 — Tool Validation and Dispatch

## Objective
Implement and test a dispatcher that validates structured tool calls and enforces authorization before accessing records.

## Implementation
- Allowed only the `check_status` tool.
- Validated tool names, arguments, and input types.
- Verified record ownership using a separate demo user identity.
- Prevented unauthorized access and modifications to records.

## Results
- **Tests Passed:** 7/7
- **Failed Tests:** 0
- **Records Unchanged:** True

## Validation vs. Authorization
Validation checks whether a tool call has the correct structure, allowed tool name, and valid arguments.

Authorization checks whether the user has permission to access the requested record.

A request can be valid in structure but still be unauthorized if the record belongs to another user.

## Files
- `day2_tools.ipynb` — Completed notebook containing the dispatcher and seven test results.
