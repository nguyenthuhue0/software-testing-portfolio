# Test Summary Report

## 1. Document Information

| Item | Details |
|------|---------|
| Document | Test Summary Report |
| Project | Real Estate Prediction System |
| Version | 1.0 |
| Tester | Nguyen Thu Hue |
| Test Type | Manual Functional Testing |
| Methodology | Agile Scrum |
| Test Period | July 2026 |
| Test Environment | Google Chrome 138 on macOS Sequoia |

---

# 2. Project Overview

The Real Estate Prediction System is a web-based application designed to estimate property prices based on user-provided information and to provide supporting features such as property search, user authentication, profile management, and customer feedback submission.

The objective of this testing cycle was to verify that the core business functionalities operate according to the specified requirements, identify functional defects, and assess the overall quality of the application before release.

---

# 3. Testing Scope

The following functional modules were included in this testing cycle.

| Module | Status |
|---------|--------|
| Authentication | Tested |
| Property Prediction | Tested |
| Property Search | Tested |
| User Profile | Tested |
| Contact & Feedback | Tested |

### Functional Areas Covered

- User Login
- User Registration
- Forgot Password
- User Logout
- Property Price Prediction
- Prediction Validation
- Property Search
- Search Filtering
- User Profile Management
- Password Change
- Avatar Upload
- Contact Form Submission
- Feedback Submission

---

# 4. Test Environment

| Item | Configuration |
|------|---------------|
| Operating System | macOS Sequoia |
| Browser | Google Chrome 138 |
| Application Type | Web Application |
| Testing Method | Manual Testing |
| Defect Tracking Tool | Jira |
| Test Case Management | Microsoft Excel |
| Documentation | GitHub Markdown |

---

# 5. Test Execution Summary

A total of **49** functional test cases were executed across five application modules.

| Module | Total | Passed | Failed |
|---------|------:|-------:|-------:|
| Authentication | 24 | 23 | 1 |
| Property Prediction | 6 | 5 | 1 |
| Property Search | 7 | 5 | 2 |
| User Profile | 6 | 5 | 1 |
| Contact & Feedback | 6 | 5 | 1 |
| **Total** | **49** | **43** | **6** |

---

# 6. Overall Test Result

| Metric | Value |
|--------|------:|
| Total Test Cases | 49 |
| Executed | 49 |
| Passed | 43 |
| Failed | 6 |
| Pass Rate | 87.76% |
| Fail Rate | 12.24% |

All planned test cases were successfully executed.

Most business-critical features functioned correctly.

Several validation and filtering issues were identified during testing and were reported through Jira.

---

# 7. Defect Summary

A total of **6 defects** were identified during the testing cycle.

| Bug ID | Summary | Priority | Status |
|---------|---------|----------|--------|
| REPT-82 | Weak password is accepted during user registration | High | Done |
| REPT-83 | Prediction accepts invalid numeric values without validation | High | In Review |
| REPT-84 | Price range filter does not return correct search results | High | In Review |
| REPT-85 | Location filter does not display properties from selected location | High | To Do |
| REPT-86 | Unsupported avatar file format is accepted | Medium | To Do |
| REPT-87 | Empty feedback can be submitted | Medium | To Do |

---

# 8. Defect Distribution

| Severity | Count |
|-----------|------:|
| High | 4 |
| Medium | 2 |
| Low | 0 |
| Critical | 0 |

### Major Findings

The majority of defects were related to:

- Missing input validation
- Search filtering logic
- File upload validation
- Form validation

No application crashes or data loss issues were observed during testing.

---

# 9. Entry Criteria Verification

The following entry criteria were satisfied before testing began.

- Application deployment completed.
- Test environment available.
- Functional requirements defined.
- Test plan approved.
- Test cases prepared.

**Status:** Completed

---

# 10. Exit Criteria Verification

The following exit criteria were evaluated after test execution.

| Criteria | Status |
|----------|--------|
| All planned test cases executed | Completed |
| Test results documented | Completed |
| Defects reported in Jira | Completed |
| Critical defects identified | Completed |
| Test Summary Report completed | Completed |

---

# 11. Risks

The following risks remain before production deployment.

- Some validation rules are not properly enforced.
- Property search filtering requires additional verification.
- User input validation should be strengthened across multiple forms.
- Remaining unresolved defects should be fixed and regression tested before release.

---

# 12. Recommendations

Based on the testing results, the following improvements are recommended.

### Authentication

- Enforce stronger password validation.
- Improve password complexity requirements.

### Property Prediction

- Validate all numeric inputs before prediction.
- Prevent negative or zero values.

### Property Search

- Review filtering logic.
- Verify combined filter conditions.
- Improve search accuracy.

### User Profile

- Restrict unsupported file types.
- Validate uploaded avatar format.

### Contact & Feedback

- Require mandatory feedback content.
- Improve client-side validation.

---

# 13. Lessons Learned

The testing cycle demonstrated that preparing detailed test cases before execution significantly improved testing efficiency.

Using Jira for defect tracking provided better visibility of issue status and facilitated communication between testing and development activities.

Maintaining structured documentation in GitHub also improved project organization and traceability.

---

# 14. Conclusion

A complete manual functional testing cycle was successfully performed for the Real Estate Prediction System.

A total of **49** test cases were executed, with **43** passing and **6** failing, resulting in an overall pass rate of **87.76%**.

The identified defects mainly involve input validation and search filtering functionality. Although the application's core business functions operate correctly, the remaining unresolved issues should be addressed before production deployment.

Overall, the application demonstrates acceptable functional stability and provides a solid foundation for future improvements following defect resolution and regression testing.

---

# 15. Deliverables

The following testing artifacts were produced during this testing cycle.

- Test Plan
- Test Cases
- Jira Project
- Bug Reports
- Test Summary Report
- GitHub Testing Portfolio

---