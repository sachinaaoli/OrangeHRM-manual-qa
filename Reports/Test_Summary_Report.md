# Test Summary Report

## Project Information

| Item             | Details                   |
| ---------------- | ------------------------- |
| Project Name     | OrangeHRM Manual Testing  |
| Application      | OrangeHRM Demo            |
| Application Type | Web Application           |
| Testing Type     | Manual Functional Testing |
| QA Engineer      | Sachina Oli               |
| Test Environment | Windows 11, Google Chrome |
| Test Duration    | August 2026               |

---

# Objective

The objective of this testing cycle was to verify the functionality, usability, and reliability of the OrangeHRM Demo application through manual testing. Testing focused on validating core business workflows, input validation, navigation, and user interface consistency.

---

# Modules Tested

* Login
* Dashboard
* Admin
* PIM
* Leave
* Recruitment
* My Info

---

# Testing Performed

* Functional Testing
* Smoke Testing
* Regression Testing
* UI Testing
* Positive Testing
* Negative Testing
* Boundary Value Analysis
* Equivalence Partitioning
* Exploratory Testing

---

# Deliverables

Completed project artifacts:

* Test Plan
* Requirements Specification
* Test Scenarios
* Test Cases
* Bug Report
* Requirement Traceability Matrix
* Test Execution Report
* Test Summary Report

---

# Test Metrics

| Metric               | Result |
| -------------------- | -----: |
| Total Requirements   |     35 |
| Total Test Scenarios |     50 |
| Total Test Cases     |    160 |
| Executed Test Cases  |    160 |
| Passed               |    154 |
| Failed               |      6 |
| Blocked              |      0 |
| Pass Rate            | 96.25% |
| Fail Rate            |  3.75% |
| Requirement Coverage |   100% |

---

# Defect Summary

| Severity      | Count |
| ------------- | ----: |
| Critical      |     0 |
| High          |     3 |
| Medium        |     9 |
| Low           |     8 |
| Total Defects |    20 |

---

# Major Findings

* Login functionality worked as expected for valid and invalid credentials.
* CRUD operations in the Admin and PIM modules were verified successfully.
* Leave application and recruitment workflows functioned correctly in most scenarios.
* Profile management features worked as expected.
* Minor validation and usability issues were identified during testing.
* No application crashes or data loss were observed during execution.

---

# Risks

* Some validation messages lack consistency.
* A few user interface elements require refinement.
* Certain updates require a manual page refresh before changes become visible.

---

# Recommendations

* Resolve all High severity defects before deployment.
* Improve input validation and error messaging.
* Standardize UI behavior across modules.
* Perform full regression testing after fixes.
* Conduct cross-browser testing before production release.
* Perform performance and security testing before deployment.

---

# Exit Criteria Review

| Criteria                         | Status    |
| -------------------------------- | --------- |
| All planned test cases executed  | Completed |
| High severity defects documented | Completed |
| RTM completed                    | Completed |
| Test execution completed         | Completed |
| Test reports prepared            | Completed |

---

# Final Assessment

The OrangeHRM Demo application demonstrated stable behavior during manual testing. Core business functionality performed as expected, and all planned test cases were executed successfully.

The identified defects are primarily related to validation, usability, and user interface behavior. None of the observed issues prevent execution of the main business workflows.

Based on the testing performed, the application is suitable for demonstration purposes. Before a production release, the documented High and Medium severity defects should be addressed, followed by a complete regression test cycle.

---

# Approval

| Role          | Name                               |
| ------------- | ---------------------------------- |
| QA Engineer   | Sachina Oli                        |
| Project       | OrangeHRM Manual Testing Portfolio |
| Report Status | Final                              |
