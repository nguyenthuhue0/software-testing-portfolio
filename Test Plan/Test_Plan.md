# Real Estate Prediction System
# Test Plan

| Document Information | |
|----------------------|--------------------------------|
| Project | Real Estate Prediction System |
| Document | Test Plan |
| Version | 1.0 |
| Prepared By | Nguyen Thu Hue |
| Test Type | Manual Functional Testing |
| Methodology | Agile Scrum |
| Date | July 2026 |

---

# 1. Introduction

This document defines the testing strategy and approach for the Real Estate Prediction System.

The purpose of this test plan is to ensure that all major business functionalities are tested before release. The testing process focuses on validating system behavior, identifying functional defects, and verifying that the application meets the expected requirements.

Testing activities will be conducted manually, and all defects will be tracked using Jira.

---

# 2. Project Overview

The Real Estate Prediction System is a web application that predicts property prices based on user-provided information.

Besides the prediction feature, the application also provides several supporting modules including user authentication, property search, user profile management, and customer feedback submission.

---

# 3. Test Scope

## In Scope

The following modules are included in this testing cycle.

- Authentication
  - User Login
  - User Registration
  - Forgot Password
  - User Logout

- Property Prediction
  - Predict Property Price
  - Input Validation
  - Prediction Result Display

- Property Search
  - Search Properties
  - Filter by Price
  - Filter by Location
  - Sort Search Results

- User Profile
  - Update Profile
  - Change Password
  - Upload Avatar

- Contact & Feedback
  - Contact Form
  - Feedback Submission

---

## Out of Scope

The following items are excluded from this testing cycle.

- Performance Testing
- Security Testing
- Load Testing
- Stress Testing
- API Testing
- Mobile Testing
- Compatibility Testing on multiple browsers

---

# 4. Test Objectives

The objectives of this testing cycle are:

- Verify that all functional requirements are implemented correctly.
- Validate user inputs throughout the application.
- Ensure all business workflows operate as expected.
- Detect and report functional defects.
- Confirm that bug fixes work correctly through regression testing.
- Provide an overall assessment of application quality before release.

---

# 5. Test Strategy

The testing approach includes:

## Functional Testing

Verify each feature against its expected behavior.

## Positive Testing

Confirm the application works correctly with valid input.

## Negative Testing

Verify the system properly handles invalid or unexpected input.

## Regression Testing

Retest affected features after defects have been fixed.

## Smoke Testing

Verify that the main functions of the application are operational before detailed testing begins.

---

# 6. Test Environment

| Item | Configuration |
|------|---------------|
| Application | Real Estate Prediction System |
| Environment | Local Development |
| Operating System | macOS Sequoia |
| Browser | Google Chrome 138 |
| Testing Type | Manual Testing |
| Bug Tracking Tool | Jira |
| Test Case Management | Microsoft Excel |
| Documentation | GitHub |

---

# 7. Test Deliverables

The following documents will be produced during testing.

- Test Plan
- Test Cases
- Bug Reports
- Jira Issues
- Test Summary Report

---

# 8. Test Schedule

| Phase | Status |
|---------|------------|
| Test Planning | Completed |
| Test Case Design | Completed |
| Test Execution | Completed |
| Bug Reporting | Completed |
| Regression Testing | Completed |
| Test Summary Report | Completed |

---

# 9. Entry Criteria

Testing will begin when the following conditions are met.

- Application is deployed successfully.
- Functional requirements are available.
- Test environment is ready.
- Test Plan has been approved.
- Test Cases have been prepared.

---

# 10. Exit Criteria

Testing will be considered complete when:

- All planned test cases have been executed.
- All discovered defects have been logged in Jira.
- High-priority defects have been reported.
- Regression testing has been completed for resolved issues.
- Test Summary Report has been prepared.

---

# 11. Roles and Responsibilities

| Role | Responsibility |
|------|----------------|
| Tester | Design test cases, execute tests, report defects, perform regression testing, prepare documentation |
| Developer | Fix reported defects |
| Product Owner | Validate business requirements |

---

# 12. Defect Management

All defects identified during testing will be recorded in Jira.

Each defect includes:

- Summary
- Description
- Steps to Reproduce
- Expected Result
- Actual Result
- Priority
- Status
- Related Test Case

Defect workflow:

```
To Do
    ↓
In Progress
    ↓
In Review
    ↓
Done
```

---

# 13. Risks

Potential risks include:

- Incomplete business requirements.
- Changes in application functionality during testing.
- Limited testing time.
- Environment instability.
- Regression defects after bug fixes.

---

# 14. Assumptions

The following assumptions apply:

- Business requirements remain stable during testing.
- Development environment is available throughout the testing cycle.
- Developers are available to resolve reported defects.
- Jira remains accessible for defect tracking.

---

# 15. Tools Used

| Tool | Purpose |
|------|---------|
| Jira | Defect Tracking |
| Microsoft Excel | Test Case Management |
| GitHub | Documentation Repository |
| Google Chrome | Test Execution |

---

# 16. Approval

This Test Plan serves as the official testing guideline for the Real Estate Prediction System and provides the overall testing strategy for the current testing cycle.

Prepared by:

**Nguyen Thu Hue**
