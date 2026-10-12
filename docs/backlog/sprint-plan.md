# Bank Management System — Sprint Plan

**Project:** Bank Management System (BMS)
**Version:** 1.0
**Authors:** Team: BMS_PES; Member 1: Tarini Arora; Member 2: Vijay Kumar; Member 3: Ronit Prasad; Member 4: Vaibhava L
**Date:** 12-10-2026
**Status:** Draft

## Sprint calendar

| Period | Dates | Purpose |
|---|---|---|
| Dry run | 12–16 Oct 2026 | Practice the workflow and resolve setup issues; not a replacement for the two planned sprints. |
| Sprint 1 | 19–23 Oct 2026 | Deliver the initial working core: login, account opening/access, deposits, withdrawals, transfers, audit logging, security foundations and CI. |
| Sprint 2 | 26–30 Oct 2026 | Deliver history/statements, reporting, notifications, remaining NFR work, and complete/freeze documentation. |

## Sprint 1 backlog (planned: 62 story points)

| Story | Backlog item | Requirement(s) | Owner | Points | Current GitHub issue |
|---|---|---|---|---:|---|
| US-01 | Login & authentication | BMS-F-001 | M1 | 5 | Pending |
| US-02 | Account lockout | BMS-F-002 | M1 | 3 | Pending |
| US-03 | Role-based access control | BMS-F-003, BMS-SR-004 | M1 | 5 | Pending |
| US-05 | Secure passwords, session timeout, data masking | BMS-SR-002, BMS-SR-003, BMS-SR-007 | M1 | 5 | Pending |
| US-06 | GitHub Actions CI pipeline | Chore | M1 | 3 | Pending |
| US-08 | Open new account & create customer login | BMS-F-010 | M2 | 5 | #1 |
| US-09 | View account & balance | BMS-F-013 | M2 | 3 | #5 |
| US-10 | Update customer details | BMS-F-011 | M2 | 3 | #7 |
| US-11 | Test automation setup (pytest) | Chore | M2 | 3 | #9 |
| US-16 | Database schema & data access layer | Chore; supports BMS-NF-003 | M3 | 3 | #2 |
| US-17 | Deposit | BMS-F-020 | M3 | 2 | #3 |
| US-18 | Withdrawal | BMS-F-021 | M3 | 3 | #4 |
| US-19 | Fund transfer | BMS-F-022 | M3 | 5 | #6 |
| US-24 | Manage employee (Teller) users | BMS-F-030 | M4 | 3 | [#17](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/17) |
| US-25 | Audit logging of all actions | BMS-SR-006 | M4 | 3 | [#18](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/18) |
| US-26 | View audit log | BMS-F-031 | M4 | 3 | [#19](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/19) |
| US-27 | Input validation & HTTPS setup | BMS-SR-005, BMS-SR-001 | M4 | 5 | [#20](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/20) |
| **Sprint 1 total** |  |  |  | **62**  |  |

## Sprint 2 backlog (planned: 36 story points)

| Story | Backlog item | Requirement(s) | Owner | Points | Current GitHub issue |
|---|---|---|---|---:|---|
| US-04 | Change password & forced first-login change | BMS-F-004 | M1 | 2 | Pending |
| US-07 | Final documentation & freeze | Chore | M1 | 2 | Pending |
| US-12 | Freeze / unfreeze / close account | BMS-F-012 | M2 | 3 | #10 |
| US-13 | Search customer / account | BMS-F-014 | M2 | 3 | #11 |
| US-14 | Usability of fund transfer flow | BMS-NF-004 | M2 | 3 | #12 |
| US-15 | Browser compatibility & responsive UI | BMS-NF-006 | M2 | 2 | #13 |
| US-20 | Transaction history & mini-statement | BMS-F-023 | M3 | 3 | #8 |
| US-21 | Statement download | BMS-F-024 | M3 | 2 | #14 |
| US-22 | Performance under load | BMS-NF-001 | M3 | 3 | #15 |
| US-23 | Atomic transactions / data integrity | BMS-NF-003 | M3 | 3 | #16 |
| US-28 | Daily transaction report | BMS-F-032 | M4 | 3 | [#21](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/21) |
| US-29 | Transaction notifications | BMS-F-033 | M4 | 3 | [#22](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/22) |
| US-30 | Health endpoint & availability | BMS-NF-002 | M4 | 2 | [#23](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/23) |
| US-31 | Audit log retention & append-only | BMS-NF-005 | M4 | 2 | [#24](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/24) |
| **Sprint 2 total** |  |  |  | **36**  |  |

## Planned allocation by member

| Member | Sprint 1 | Sprint 2 | Total |
|---|---:|---:|---:|
| M1 | 21 | 4 | 25 |
| M2 | 14 | 11 | 25 |
| M3 | 13 | 11 | 24 |
| M4 | 14 | 10 | 24 |
| **Team** | **62** | **36** | **98** |

## Planning notes

- Estimates use the agreed Fibonacci story-point scale (1, 2, 3, 5, 8).
- These are planned allocations from the shared Baseline v1.2, not evidence that work has started or passed testing. Issue references above reflect the latest repository issue list; US-24–US-31 are created and verified as GitHub issues #17–#24, with links recorded above and their Project board sprint assignments and story points verified. US-01–US-07 remain pending verification/creation.
- The team may rebalance backlog entries on 19 October as allowed by the course instructions. Any change should be reflected consistently in the GitHub issues, Project board, and this file.
- Sprint 1 objective: working login, account operations, deposit/withdrawal/transfer, audit logging, and CI.
- Sprint 2 objective: transaction history/statements, reports, notifications, NFR work, and documentation freeze.
- GitHub issue numbers and Project-board field values must be confirmed against the live repository/Project when the issues and Project are available.
