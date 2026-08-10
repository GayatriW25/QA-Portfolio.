# WorkerHub – Test Cases

| TC ID | Module | Test Case | Precondition | Steps | Expected Result |
|------|--------|-----------|-------------|-------|----------------|
| TC_001 | Registration | Verify Worker Registration with valid details | Registration page is open | 1. Enter valid details<br>2. Select Worker<br>3. Click Register | User should be registered successfully. |
| TC_002 | Registration | Verify mandatory fields | Registration page is open | 1. Leave mandatory fields blank<br>2. Click Register | Validation messages should be displayed. |
| TC_003 | Login | Verify login with valid credentials | User account exists | 1. Enter valid username and password<br>2. Click Login | User should be redirected to the dashboard. |
| TC_004 | Login | Verify login with invalid password | User account exists | 1. Enter valid username<br>2. Enter wrong password<br>3. Click Login | "Invalid Username or Password" message should be displayed. |
| TC_005 | Job Posting | Verify Contractor can post a job | Contractor is logged in | 1. Click Post Job<br>2. Enter job details<br>3. Submit | Job should be posted successfully. |
| TC_006 | Job Search | Verify Worker can search jobs | Worker is logged in | 1. Enter keyword<br>2. Click Search | Matching jobs should be displayed. |
| TC_007 | Job Application | Verify Worker can apply for a job | Worker is logged in | 1. Open a job<br>2. Click Apply | Application should be submitted successfully. |
| TC_008 | Applicants | Verify Contractor can view applicants | Contractor has posted a job | 1. Open Posted Jobs<br>2. Click View Applicants | Applicant list should be displayed. |
| TC_009 | Notifications | Verify notification after application acceptance | Application accepted | 1. Accept application | Worker should receive an acceptance notification. |
| TC_010 | Logout | Verify Logout functionality | User is logged in | 1. Click Logout | User should be logged out and redirected to the login page. |
