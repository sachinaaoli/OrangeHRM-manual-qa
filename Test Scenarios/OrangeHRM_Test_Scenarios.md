# OrangeHRM Test Scenarios

## Project

OrangeHRM Demo Manual Testing

---

# Login Module

| Scenario ID | Requirement ID | Test Scenario                                                          |
| ----------- | -------------- | ---------------------------------------------------------------------- |
| TS-001      | FR-001         | Verify login with valid username and valid password.                   |
| TS-002      | FR-002         | Verify login with an invalid username.                                 |
| TS-003      | FR-003         | Verify login with an invalid password.                                 |
| TS-004      | FR-004         | Verify login with both fields empty.                                   |
| TS-005      | FR-004         | Verify login with username empty.                                      |
| TS-006      | FR-004         | Verify login with password empty.                                      |
| TS-007      | FR-005         | Verify the password is masked.                                         |
| TS-008      | FR-006         | Verify the Forgot Password link opens the Reset Password page.         |
| TS-009      | FR-007         | Verify the user logs out successfully.                                 |
| TS-010      | FR-001         | Verify leading and trailing spaces are handled correctly during login. |

---

# Dashboard Module

| Scenario ID | Requirement ID | Test Scenario                                        |
| ----------- | -------------- | ---------------------------------------------------- |
| TS-011      | FR-008         | Verify the dashboard appears after successful login. |
| TS-012      | FR-009         | Verify Quick Launch widgets are displayed.           |
| TS-013      | FR-010         | Verify dashboard widgets load correctly.             |
| TS-014      | FR-011         | Verify the side menu is displayed.                   |
| TS-015      | FR-011         | Verify navigation from the dashboard to each module. |

---

# Admin Module

| Scenario ID | Requirement ID | Test Scenario                                                       |
| ----------- | -------------- | ------------------------------------------------------------------- |
| TS-016      | FR-012         | Verify the User Management page opens successfully.                 |
| TS-017      | FR-013         | Verify a new user is added successfully.                            |
| TS-018      | FR-013         | Verify validation messages for required fields while adding a user. |
| TS-019      | FR-014         | Verify searching by username.                                       |
| TS-020      | FR-014         | Verify searching by user role.                                      |
| TS-021      | FR-015         | Verify editing an existing user.                                    |
| TS-022      | FR-016         | Verify deleting an existing user.                                   |
| TS-023      | FR-016         | Verify the confirmation dialog appears before deletion.             |

---

# PIM Module

| Scenario ID | Requirement ID | Test Scenario                                    |
| ----------- | -------------- | ------------------------------------------------ |
| TS-024      | FR-017         | Verify adding a new employee.                    |
| TS-025      | FR-017         | Verify validation for mandatory employee fields. |
| TS-026      | FR-018         | Verify employee search by name.                  |
| TS-027      | FR-018         | Verify employee search by employee ID.           |
| TS-028      | FR-019         | Verify editing employee details.                 |
| TS-029      | FR-020         | Verify deleting an employee.                     |
| TS-030      | FR-017         | Verify employee ID uniqueness.                   |

---

# Leave Module

| Scenario ID | Requirement ID | Test Scenario                                             |
| ----------- | -------------- | --------------------------------------------------------- |
| TS-031      | FR-021         | Verify leave application submission.                      |
| TS-032      | FR-021         | Verify validation for mandatory leave fields.             |
| TS-033      | FR-022         | Verify viewing leave history.                             |
| TS-034      | FR-023         | Verify canceling a leave request.                         |
| TS-035      | FR-021         | Verify leave balance is updated correctly after approval. |

---

# Recruitment Module

| Scenario ID | Requirement ID | Test Scenario                                     |
| ----------- | -------------- | ------------------------------------------------- |
| TS-036      | FR-024         | Verify adding a candidate.                        |
| TS-037      | FR-024         | Verify validation for mandatory candidate fields. |
| TS-038      | FR-025         | Verify searching candidates by name.              |
| TS-039      | FR-026         | Verify editing candidate information.             |
| TS-040      | FR-027         | Verify deleting a candidate.                      |

---

# My Info Module

| Scenario ID | Requirement ID | Test Scenario                                                         |
| ----------- | -------------- | --------------------------------------------------------------------- |
| TS-041      | FR-028         | Verify personal information is displayed correctly.                   |
| TS-042      | FR-029         | Verify editing personal information.                                  |
| TS-043      | FR-030         | Verify uploading a profile picture.                                   |
| TS-044      | FR-030         | Verify uploading an unsupported file type is rejected.                |
| TS-045      | FR-029         | Verify mandatory field validation while editing personal information. |

---

# General Scenarios

| Scenario ID | Requirement ID | Test Scenario                                                            |
| ----------- | -------------- | ------------------------------------------------------------------------ |
| TS-046      | NFR-001        | Verify pages load within an acceptable time.                             |
| TS-047      | NFR-002        | Verify consistent UI across modules.                                     |
| TS-048      | NFR-003        | Verify error messages are clear and readable.                            |
| TS-049      | NFR-004        | Verify the application displays correctly at common desktop resolutions. |
| TS-050      | NFR-005        | Verify the user session ends after logout.                               |
