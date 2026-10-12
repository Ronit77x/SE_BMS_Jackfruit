# Bank Management System — Backlog Coverage Check

**Project:** Bank Management System (BMS)
**Version:** 1.0
**Authors:** Team: BMS_PES; Member 1: Tarini Arora; Member 2: Vijay Kumar; Member 3: Ronit Prasad; Member 4: Vaibhava L
**Date:** 12-10-2026
**Status:** Draft — Member 4 GitHub and Project verification complete; remaining team backlog verification pending

## Purpose and verification status

This table maps every fixed requirement ID in Baseline v1.2 to the planned backlog story or stories. The story mapping and story IDs are taken from Part A §7 of the Member 4 task pack.

**Verified Member 4 status:** Issues #17–#24 exist, are open, and are assigned to `Vaibhav-alt0246`. All eight are project items in **BMS Backlog & Sprints** with Status = **Backlog**. US-24–US-27 are in Sprint 1 for 14 total Member 4 story points; US-28–US-31 are in Sprint 2 for 10 points; Member 4 total is 24 points. The Project fields and values were verified after the board update.

## Requirement-to-story coverage

| Requirement ID | Short requirement | Planned story ID(s) | GitHub issue number | Coverage |
|---|---|---|---|---|
| BMS-F-001 | Authenticate user / create session | US-01 | Pending | Planned |
| BMS-F-002 | Lock user after 3 failed logins | US-02 | Pending | Planned |
| BMS-F-003 | Enforce role-based access | US-03 | Pending | Planned |
| BMS-F-004 | Change password / force first-login change | US-04 | Pending | Planned |
| BMS-F-010 | Teller opens account and creates customer login when needed | US-08 | #1 | Issue exists; verify mapping |
| BMS-F-011 | Teller updates customer contact details | US-10 | #7 | Issue exists; verify mapping |
| BMS-F-012 | Admin freezes, unfreezes or closes account | US-12 | #10 | Issue exists; verify mapping |
| BMS-F-013 | Customer views own account and balance | US-09 | #5 | Issue exists; verify story mapping |
| BMS-F-014 | Teller searches customer | US-13 | #11 | Issue exists; verify story mapping |
| BMS-F-020 | Cash deposit | US-17 | #3 | Issue exists; verify story mapping |
| BMS-F-021 | Withdrawal with balance and daily-limit rules | US-18 | #4 | Issue exists; verify story mapping |
| BMS-F-022 | Customer fund transfer | US-19 | #6 | Issue exists; verify story mapping |
| BMS-F-023 | Transaction history / mini-statement | US-20 | #8 | Issue exists; verify story mapping |
| BMS-F-024 | Download account statement | US-21 | #14 | Issue exists; verify story mapping |
| BMS-F-030 | Admin manages Teller users | US-24 | [#17](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/17) | Verified; open, assigned, and in Project Backlog |
| BMS-F-031 | Admin views filtered audit log | US-26 | [#19](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/19) | Verified; open, assigned, and in Project Backlog |
| BMS-F-032 | Daily transaction summary | US-28 | [#21](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/21) | Verified; open, assigned, and in Project Backlog |
| BMS-F-033 | Simulated notification after debit/credit | US-29 | [#22](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/22) | Verified; open, assigned, and in Project Backlog |
| BMS-NF-001 | Performance at 50 concurrent users | US-22 | #15 | Issue exists; verify story mapping |
| BMS-NF-002 | 99.5% monthly availability and health endpoint | US-30 | [#23](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/23) | Verified; open, assigned, and in Project Backlog |
| BMS-NF-003 | Atomic financial transactions | US-16, US-23 | US-16: #2; US-23: #16 | Both planned stories have issues; verify mapping against baseline |
| BMS-NF-004 | First-time-user transfer usability | US-14 | #12 | Issue exists; verify story mapping |
| BMS-NF-005 | Append-only audit log retained for at least 5 years | US-31 | [#24](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/24) | Verified; open, assigned, and in Project Backlog |
| BMS-NF-006 | Browser compatibility and 360 px UI | US-15 | #13 | Issue exists; verify story mapping |
| BMS-SR-001 | TLS 1.2+ for client-server communication | US-27 | [#20](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/20) | Verified; open, assigned, and in Project Backlog |
| BMS-SR-002 | Salted bcrypt/argon2 password hashes; never log passwords | US-05 | Pending | Planned |
| BMS-SR-003 | Session expires after 10 minutes inactivity | US-05 | Pending | Planned |
| BMS-SR-004 | Server-side role authorization every request | US-03 | Pending | Planned |
| BMS-SR-005 | Input validation and parameterized queries against SQL injection/XSS | US-27 | [#20](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/20) | Verified; open, assigned, and in Project Backlog |
| BMS-SR-006 | Audit log for login, financial and admin actions | US-25 | [#18](https://github.com/Ronit77x/SE_Jackfruit_Bank-Management-System/issues/18) | Verified; open, assigned, and in Project Backlog |
| BMS-SR-007 | Mask account numbers and encrypt ID-proof numbers at rest | US-05 | Pending | Planned |

## Coverage and board checklist

Legend: **✔** = the requirement has a planned story and the referenced issue was found; **✘** = the issue is missing or has not been verified. A ✔ here means issue presence only, not implementation or test completion.

| Check | Current status | Evidence / next action |
|---|---|---|
| All 18 functional requirement IDs mapped | Planned | All BMS-F IDs listed above; verify against actual GitHub issues after creation. |
| All 6 non-functional requirement IDs mapped | Planned | All BMS-NF IDs listed above; NF-003 maps to US-16 and US-23 as specified in the baseline. |
| All 7 security requirement IDs mapped | Planned | All BMS-SR IDs listed above. |
| All 31 requirement IDs represented | Planned mapping complete; team-wide live verification pending | 18 FR + 6 NFR + 7 SR = 31 IDs. |
| All 31 stories have issue numbers | ✘ Partial | Issues #1–#24 cover US-08–US-31; US-01–US-07 remain to be verified/created. |
| Each issue has the correct assignee | ✘ Pending | US-08–US-23 issues exist and are assigned, but full ownership/story mapping and remaining stories need verification. |
| Each issue has story points | ✘ Pending | Confirm points match Baseline v1.2 and the sprint plan. |
| Each issue has a sprint | ✘ Pending | Confirm Sprint 1 / Sprint 2 fields and dates on the Project board. |
| Project is linked to the repository | ✔ Verified | All 24 repository issues are project items in **BMS Backlog & Sprints**. |
| M4 issues US-24–US-31 created and assigned to M4 | ✔ Verified | Issues #17–#24 are open, assigned to `Vaibhav-alt0246`, and present in the Project with Status = Backlog. |

## Follow-up actions

1. Verify or create the remaining US-01–US-07 issues and replace their pending references when confirmed.
2. Complete team-wide verification of issue ownership, story points, sprint assignments, and Project fields.
3. Re-run this coverage check after the remaining backlog items are verified.
