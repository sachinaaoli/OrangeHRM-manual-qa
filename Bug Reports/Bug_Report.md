# OrangeHRM Bug Report

## Project

OrangeHRM Demo Manual Testing

---

| Bug ID  | Module      | Summary                                                                             | Severity | Priority | Status |
| ------- | ----------- | ----------------------------------------------------------------------------------- | -------- | -------- | ------ |
| BUG-001 | Login       | Username field accepts leading and trailing spaces before validation                | Medium   | Medium   | Open   |
| BUG-002 | Login       | Error message remains visible after correcting credentials until next login attempt | Low      | Low      | Open   |
| BUG-003 | Login       | Forgot Password page allows empty username submission                               | High     | High     | Open   |
| BUG-004 | Dashboard   | Widget loading animation appears longer than expected on slow connections           | Low      | Low      | Open   |
| BUG-005 | Admin       | Duplicate username validation appears only after clicking Save                      | Medium   | Medium   | Open   |
| BUG-006 | Admin       | Search filters are not cleared immediately after clicking Reset                     | Medium   | Medium   | Open   |
| BUG-007 | Admin       | Delete confirmation dialog closes when clicking outside the modal                   | Low      | Low      | Open   |
| BUG-008 | PIM         | Employee photo upload accepts files larger than the documented size limit           | Medium   | Medium   | Open   |
| BUG-009 | PIM         | Employee search is case sensitive for some name combinations                        | Medium   | Medium   | Open   |
| BUG-010 | PIM         | Employee ID field accepts leading spaces                                            | Low      | Low      | Open   |
| BUG-011 | Leave       | Leave comment field accepts only whitespace characters                              | Low      | Low      | Open   |
| BUG-012 | Leave       | Invalid date range validation message is unclear                                    | Medium   | Medium   | Open   |
| BUG-013 | Leave       | Leave balance is not refreshed until page reload                                    | High     | High     | Open   |
| BUG-014 | Recruitment | Resume upload error message does not specify supported file formats                 | Medium   | Medium   | Open   |
| BUG-015 | Recruitment | Candidate search retains previous filters after browser refresh                     | Low      | Low      | Open   |
| BUG-016 | Recruitment | Email validation accepts consecutive dots before the domain                         | Medium   | High     | Open   |
| BUG-017 | My Info     | Profile image preview is not updated immediately after upload                       | Medium   | Medium   | Open   |
| BUG-018 | My Info     | Name fields allow multiple consecutive spaces                                       | Low      | Low      | Open   |
| BUG-019 | My Info     | Save button remains enabled when no data has changed                                | Low      | Low      | Open   |
| BUG-020 | General     | Some pages show inconsistent spacing between form fields                            | Low      | Low      | Open   |

---

# Detailed Bug Reports

## BUG-001

**Title:** Username field accepts leading and trailing spaces before validation

**Module:** Login

**Severity:** Medium

**Priority:** Medium

**Environment:** Chrome, Windows 11

### Steps to Reproduce

1. Open the Login page.
2. Enter spaces before and after a valid username.
3. Enter a valid password.
4. Click Login.

### Expected Result

The application should trim unnecessary spaces before validating the username.

### Actual Result

The application attempts validation using the entered value, including spaces.

---

## BUG-005

**Title:** Duplicate username validation appears only after clicking Save

**Module:** Admin

**Severity:** Medium

**Priority:** Medium

### Steps to Reproduce

1. Navigate to Admin.
2. Click Add User.
3. Enter an existing username.
4. Complete the remaining fields.
5. Click Save.

### Expected Result

The system should identify the duplicate username before form submission or clearly highlight the field immediately after validation.

### Actual Result

The duplicate username error is shown only after the Save action.

---

## BUG-013

**Title:** Leave balance is not refreshed until page reload

**Module:** Leave

**Severity:** High

**Priority:** High

### Steps to Reproduce

1. Submit and approve a leave request.
2. Return to the Leave page.
3. Check the leave balance.

### Expected Result

The leave balance updates immediately after the request status changes.

### Actual Result

The previous balance remains visible until the page is refreshed.

---

## BUG-016

**Title:** Email validation accepts consecutive dots before the domain

**Module:** Recruitment

**Severity:** Medium

**Priority:** High

### Steps to Reproduce

1. Open Add Candidate.
2. Enter an email such as `john..doe@example.com`.
3. Complete the remaining required fields.
4. Save the candidate.

### Expected Result

The application should reject invalid email formats.

### Actual Result

The email passes validation and the candidate is saved.

---

## BUG-017

**Title:** Profile image preview is not updated immediately after upload

**Module:** My Info

**Severity:** Medium

**Priority:** Medium

### Steps to Reproduce

1. Open My Info.
2. Upload a new profile picture.
3. Save the changes.

### Expected Result

The newly uploaded image should appear immediately after saving.

### Actual Result

The previous image remains visible until the page is refreshed.
