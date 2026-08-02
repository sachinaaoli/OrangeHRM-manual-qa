# Test Execution Report

## Project Information

**Project Name:** OrangeHRM Manual Testing

**Application:** OrangeHRM Demo

**Application URL:** https://opensource-demo.orangehrmlive.com/

**Testing Type:** Manual Testing

**QA Engineer:** Sachina Oli

**Execution Date:** July 2026

---

# Test Environment

| Item             | Details                               |
| ---------------- | ------------------------------------- |
| Operating System | Windows 11                            |
| Browser          | Google Chrome (Latest Stable Version) |
| Test Type        | Manual Testing                        |
| Environment      | Demo Environment                      |

---

# Execution Summary

| Metric              |  Count |
| ------------------- | -----: |
| Total Test Cases    |    160 |
| Executed Test Cases |    160 |
| Passed              |    154 |
| Failed              |      6 |
| Blocked             |      0 |
| Not Executed        |      0 |
| Pass Rate           | 96.25% |
| Fail Rate           |  3.75% |

---

# Module-wise Execution

| Module      | Total | Passed | Failed |
| ----------- | ----: | -----: | -----: |
| Login       |    20 |     19 |      1 |
| Dashboard   |     5 |      5 |      0 |
| Admin       |    30 |     28 |      2 |
| PIM         |    30 |     29 |      1 |
| Leave       |    25 |     24 |      1 |
| Recruitment |    30 |     29 |      1 |
| My Info     |    25 |     25 |      0 |
| Total       |   165 |    159 |      6 |

---

# Failed Test Cases

| Test Case ID | Module      | Related Bug | Status |
| ------------ | ----------- | ----------- | ------ |
| TC-LOGIN-009 | Login       | BUG-003     | Failed |
| TC-ADMIN-026 | Admin       | BUG-006     | Failed |
| TC-ADMIN-020 | Admin       | BUG-007     | Failed |
| TC-PIM-009   | PIM         | BUG-008     | Failed |
| TC-LEAVE-019 | Leave       | BUG-013     | Failed |
| TC-REC-010   | Recruitment | BUG-014     | Failed |

---

# Defect Summary

| Severity | Count |
| -------- | ----: |
| Critical |     0 |
| High     |     3 |
| Medium   |     9 |
| Low      |     8 |
| Total    |    20 |

---

# Execution Status by Priority

| Priority | Executed | Passed | Failed |
| -------- | -------: | -----: | -----: |
| High     |       72 |     68 |      4 |
| Medium   |       60 |     58 |      2 |
| Low      |       28 |     28 |      0 |

---

# Exit Criteria

| Criteria                         | Status |
| -------------------------------- | ------ |
| All planned test cases executed  | Yes    |
| High-priority defects identified | Yes    |
| Test execution completed         | Yes    |
| Bug report prepared              | Yes    |
| RTM completed                    | Yes    |

---

# Risks Observed

* Minor UI inconsistencies across modules.
* Validation messages are inconsistent in some forms.
* Some updates require a page refresh before changes become visible.
* Error messages could provide clearer guidance.

---

# Recommendations

* Resolve all High severity defects before production.
* Standardize validation messages across all forms.
* Improve client-side validation for mandatory fields.
* Refresh UI data automatically after successful updates.
* Perform regression testing after defect fixes.

---

# Overall Result

The OrangeHRM Demo application successfully passed most functional test cases. Core features such as authentication, employee management, leave management, recruitment, and profile management worked as expected.

A small number of functional and usability issues were identified. These defects have been documented in the Bug Report and should be addressed before release. Based on the executed test cases, the application is considered stable for demonstration purposes, with a pass rate of 96.25%.
