# OrangeHRM Requirements Specification

## Project

OrangeHRM Demo Manual Testing

## Application

https://opensource-demo.orangehrmlive.com/

## Purpose

This document lists the functional requirements identified during requirement analysis. These requirements will be used to create test scenarios, test cases, and the Requirement Traceability Matrix (RTM).

---

# Module 1: Login

### FR-001

The system shall allow users to log in with a valid username and password.

### FR-002

The system shall display an error message when an invalid username is entered.

### FR-003

The system shall display an error message when an invalid password is entered.

### FR-004

The system shall not allow login when both username and password are empty.

### FR-005

The Password field shall mask user input.

### FR-006

The "Forgot your password?" link shall navigate to the Reset Password page.

### FR-007

The system shall allow users to log out successfully.

---

# Module 2: Dashboard

### FR-008

The dashboard shall be displayed after successful login.

### FR-009

The dashboard shall display the Quick Launch section.

### FR-010

The dashboard shall display employee widgets.

### FR-011

The dashboard menu shall be accessible.

---

# Module 3: Admin

### FR-012

The admin user shall view the User Management page.

### FR-013

The admin user shall add a new system user.

### FR-014

The admin user shall search users.

### FR-015

The admin user shall edit user details.

### FR-016

The admin user shall delete a user.

---

# Module 4: PIM

### FR-017

The user shall add a new employee.

### FR-018

The user shall search employees.

### FR-019

The user shall edit employee details.

### FR-020

The user shall delete an employee.

---

# Module 5: Leave

### FR-021

The user shall apply for leave.

### FR-022

The user shall view leave records.

### FR-023

The user shall cancel a leave request.

---

# Module 6: Recruitment

### FR-024

The user shall add a candidate.

### FR-025

The user shall search candidates.

### FR-026

The user shall edit candidate details.

### FR-027

The user shall delete a candidate.

---

# Module 7: My Info

### FR-028

The user shall view personal information.

### FR-029

The user shall edit personal information.

### FR-030

The user shall upload a profile picture.

---

# Non Functional Requirements

### NFR-001

The application shall load each page within an acceptable time.

### NFR-002

The application shall have a consistent user interface.

### NFR-003

The application shall display readable error messages.

### NFR-004

The application shall be responsive on common desktop resolutions.

### NFR-005

The application shall maintain user session until logout or session timeout.
