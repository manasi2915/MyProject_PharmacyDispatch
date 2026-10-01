# 01 — Requirements Engineering

**Project:** Pharmacy Expiry & Re-order Dispatch Engine (Problem Statement #15)

## Contents

| File | Description |
|------|-------------|
| `Requirements_Table.docx` | Functional Requirements (FR-001 to FR-005), Non-Functional Requirements (NFR-001, NFR-002), and the Requirements Traceability Matrix (RTM) |

## Summary

- **5 Functional Requirements:** FEFO enforcement, batch registration, FEFO picking list, low-stock detection, supplier PO status update
- **2 Non-Functional Requirements:** automated PO dispatch (performance & security), immutable 3-year audit log (data integrity & compliance)
- Each requirement has an ID, Type, Description, Priority, Acceptance Criteria, and Rationale

## Requirements Traceability Matrix

| Req ID | Use Case(s) | Actor(s) | Test Case |
|--------|-------------|----------|-----------|
| FR-001 | UC-02, UC-03 | Pharmacy Clerk | TC-01 |
| FR-002 | UC-01 | Pharmacy Clerk | TC-02 |
| FR-003 | UC-04, UC-03 | Pharmacy Clerk | TC-03 |
| FR-004 | UC-05 | System Scheduler | TC-04 |
| FR-005 | UC-08 | Inventory Supplier | TC-05 |
| NFR-001 | UC-06, UC-07 | System Scheduler, Inventory Supplier | TC-06 |
| NFR-002 | UC-01, UC-02, UC-06, UC-07, UC-08 | All actors | TC-07 |

All 7 requirements trace to at least one use case and test case, and all 8 use cases trace back to at least one requirement.
The full RTM, including test case descriptions and backward traceability, is in `Requirements_Table.docx`.
