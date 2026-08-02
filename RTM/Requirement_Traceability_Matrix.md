# Requirement Traceability Matrix (RTM)

## Project

OrangeHRM Manual Testing

---

| Requirement ID | Requirement Description                | Scenario ID(s)         | Test Case ID(s)                                                                      | Status  |
| -------------- | -------------------------------------- | ---------------------- | ------------------------------------------------------------------------------------ | ------- |
| FR-001         | User can log in with valid credentials | TS-001, TS-010         | TC-LOGIN-001, TC-LOGIN-011, TC-LOGIN-012, TC-LOGIN-017, TC-LOGIN-020                 | Covered |
| FR-002         | Invalid username displays an error     | TS-002                 | TC-LOGIN-002, TC-LOGIN-004, TC-LOGIN-015                                             | Covered |
| FR-003         | Invalid password displays an error     | TS-003                 | TC-LOGIN-003, TC-LOGIN-014, TC-LOGIN-016                                             | Covered |
| FR-004         | Required field validation on Login     | TS-004, TS-005, TS-006 | TC-LOGIN-005, TC-LOGIN-006, TC-LOGIN-007, TC-LOGIN-018                               | Covered |
| FR-005         | Password is masked                     | TS-007                 | TC-LOGIN-008, TC-LOGIN-019                                                           | Covered |
| FR-006         | Forgot Password functionality          | TS-008                 | TC-LOGIN-009                                                                         | Covered |
| FR-007         | Logout functionality                   | TS-009                 | TC-LOGIN-010                                                                         | Covered |
| FR-008         | Dashboard loads after login            | TS-011                 | Covered during smoke testing                                                         | Covered |
| FR-009         | Dashboard displays Quick Launch        | TS-012                 | Dashboard verification                                                               | Covered |
| FR-010         | Dashboard widgets load correctly       | TS-013                 | Dashboard verification                                                               | Covered |
| FR-011         | Navigation menu works correctly        | TS-014, TS-015         | Dashboard navigation testing                                                         | Covered |
| FR-012         | Access Admin module                    | TS-016                 | TC-ADMIN-001, TC-ADMIN-030                                                           | Covered |
| FR-013         | Add new user                           | TS-017, TS-018         | TC-ADMIN-002 to TC-ADMIN-011, TC-ADMIN-024, TC-ADMIN-025, TC-ADMIN-026, TC-ADMIN-029 | Covered |
| FR-014         | Search user                            | TS-019, TS-020         | TC-ADMIN-012, TC-ADMIN-013, TC-ADMIN-014, TC-ADMIN-015, TC-ADMIN-023, TC-ADMIN-028   | Covered |
| FR-015         | Edit user                              | TS-021                 | TC-ADMIN-016, TC-ADMIN-017, TC-ADMIN-018, TC-ADMIN-019                               | Covered |
| FR-016         | Delete user                            | TS-022, TS-023         | TC-ADMIN-020, TC-ADMIN-021, TC-ADMIN-022                                             | Covered |
| FR-017         | Add employee                           | TS-024, TS-025, TS-030 | TC-PIM-001 to TC-PIM-010, TC-PIM-024, TC-PIM-025, TC-PIM-026, TC-PIM-029, TC-PIM-030 | Covered |
| FR-018         | Search employee                        | TS-026, TS-027         | TC-PIM-011 to TC-PIM-015, TC-PIM-027                                                 | Covered |
| FR-019         | Edit employee                          | TS-028                 | TC-PIM-016 to TC-PIM-020, TC-PIM-028                                                 | Covered |
| FR-020         | Delete employee                        | TS-029                 | TC-PIM-021, TC-PIM-022, TC-PIM-023                                                   | Covered |
| FR-021         | Apply leave                            | TS-031, TS-032, TS-035 | TC-LEAVE-001 to TC-LEAVE-010, TC-LEAVE-019 to TC-LEAVE-025                           | Covered |
| FR-022         | View leave history                     | TS-033                 | TC-LEAVE-011 to TC-LEAVE-015, TC-LEAVE-023                                           | Covered |
| FR-023         | Cancel leave request                   | TS-034                 | TC-LEAVE-016, TC-LEAVE-017, TC-LEAVE-018                                             | Covered |
| FR-024         | Add candidate                          | TS-036, TS-037         | TC-REC-001 to TC-REC-012, TC-REC-026 to TC-REC-030                                   | Covered |
| FR-025         | Search candidates                      | TS-038                 | TC-REC-013 to TC-REC-017, TC-REC-025                                                 | Covered |
| FR-026         | Edit candidate                         | TS-039                 | TC-REC-018 to TC-REC-021                                                             | Covered |
| FR-027         | Delete candidate                       | TS-040                 | TC-REC-022, TC-REC-023, TC-REC-024                                                   | Covered |
| FR-028         | View personal information              | TS-041                 | TC-MI-001, TC-MI-002, TC-MI-020, TC-MI-024                                           | Covered |
| FR-029         | Edit personal information              | TS-042, TS-045         | TC-MI-003 to TC-MI-011, TC-MI-016 to TC-MI-023, TC-MI-025                            | Covered |
| FR-030         | Upload profile picture                 | TS-043, TS-044         | TC-MI-012, TC-MI-013, TC-MI-014, TC-MI-015                                           | Covered |
| NFR-001        | Acceptable page load time              | TS-046                 | Exploratory testing                                                                  | Covered |
| NFR-002        | Consistent user interface              | TS-047                 | UI inspection                                                                        | Covered |
| NFR-003        | Clear error messages                   | TS-048                 | Validation testing                                                                   | Covered |
| NFR-004        | Desktop responsiveness                 | TS-049                 | UI testing                                                                           | Covered |
| NFR-005        | Session management                     | TS-050                 | Logout and session testing                                                           | Covered |

---

## RTM Summary

| Metric                      | Value |
| --------------------------- | ----: |
| Functional Requirements     |    30 |
| Non Functional Requirements |     5 |
| Total Requirements          |    35 |
| Test Scenarios              |    50 |
| Test Cases                  |   160 |
| Requirement Coverage        |  100% |
| Uncovered Requirements      |     0 |

---

## Coverage Status

* Total Requirements: 35
* Covered Requirements: 35
* Requirement Coverage: 100%
* All requirements are mapped to one or more test scenarios.
* All test scenarios are mapped to one or more test cases.
* No requirement is left untested.
