# WorkerHub – Test Plan

## 1. Introduction
This Test Plan defines the testing strategy for **WorkerHub**, a desktop-based job portal application developed using Java Swing and MySQL. The application connects workers and contractors by allowing contractors to post jobs and workers to search and apply for them. The purpose of testing is to ensure that all functionalities work correctly, data is stored accurately, and the application meets the specified requirements.

---

## 2. Objectives

- Verify all major functionalities of the WorkerHub application.
- Validate user registration and login for different user roles.
- Ensure job posting and job application workflows function correctly.
- Verify database consistency using SQL queries.
- Identify and report defects before deployment.

---

## 3. Project Description

WorkerHub is a desktop application that provides a platform for workers to find jobs and contractors to hire workers. The application supports three user roles:

- Worker
- Contractor
- Admin

Workers can register, search for jobs, apply for jobs, and manage their profiles. Contractors can post jobs, view applicants, and manage job postings. Admin manages the overall system.

---

## 4. Scope

### In Scope

- User Registration
- User Login
- Role-based Authentication
- Worker Dashboard
- Contractor Dashboard
- Job Posting
- Job Search
- Job Application
- Applicant Management
- Notifications
- Profile Management
- Logout
- Database Validation

### Out of Scope

- Performance Testing
- Load Testing
- Security Testing
- Mobile Application Testing
- Cross-browser Testing

---

## 5. Testing Types

The following testing types will be performed:

- Functional Testing
- Smoke Testing
- Regression Testing
- Integration Testing
- Database Testing (SQL Validation)

---

## 6. Modules to be Tested

- Registration Module
- Login Module
- Worker Module
- Contractor Module
- Admin Module
- Job Posting Module
- Job Search Module
- Job Application Module
- Notification Module
- Profile Management Module

---

## 7. Test Environment

| Component | Details |
|-----------|---------|
| Operating System | Windows 10/11 |
| Programming Language | Java |
| IDE | NetBeans |
| Database | MySQL |
| Database Connectivity | JDBC |
| Version Control | Git & GitHub |

---

## 8. Entry Criteria

- Application build is available.
- Database is configured successfully.
- Test environment is ready.
- Functional requirements are available.

---

## 9. Exit Criteria

- All planned test cases are executed.
- Critical and High severity defects are resolved.
- Test execution is completed successfully.
- Test Summary Report is prepared.

---

## 10. Deliverables

- Test Plan
- Test Scenarios
- Test Cases
- Bug Report
- Requirement Traceability Matrix (RTM)
- SQL Validation Report

---

## 11. Risks & Assumptions

### Risks
- Requirement changes during testing.
- Database connectivity issues.
- Incomplete test data.

### Assumptions
- Application is stable for testing.
- Test environment remains available throughout the testing phase.
- All required modules are implemented before testing begins.
