# Hotel Management System

---

## Test Documentation Included

This repository/project contains structured test artifacts used to validate the system.

### 1. Test Cases

Functional test cases were executed to verify correct system behavior.

**Sample Coverage:**

* Add guest with valid inputs
* Validate required guest fields
* Add room with valid details
* Create booking with valid data
* Prevent booking creation with missing required fields

All executed test cases resulted in **PASS** status.

---

### 2. Bug Reports

Identified issues during testing were documented and resolved.

| Bug ID | Module                  | Severity | Status |
| ------ | ----------------------- | -------- | ------ |
| BUG-01 | Guest Form Validation   | High     | Closed |
| BUG-02 | Booking Form Validation | High     | Closed |

Both bugs were related to form validation and were successfully fixed.

---

### 3. Traceability

Traceability ensures that all test cases are executed and mapped correctly.

* **Test Run Date:** December 17, 2025
* **Total Test Cases:** 5
* **Passed:** 5
* **Failed:** 0

All test cases were executed successfully and verified.

---

### 4. Retest Logs

After fixing reported bugs, retesting was conducted to confirm resolutions.

| Requirement ID | Description                   | Test Case   | Bug ID | Verified |
| -------------- | ----------------------------- | ----------- | ------ | -------- |
| REQ-01         | Guest form input validation   | TC-GUEST-02 | BUG-01 | Yes      |
| REQ-02         | Booking form input validation | TC-BOOK-02  | BUG-02 | Yes      |

---

### 5. Penetration Testing

Basic security testing was performed using OWASP ZAP.

| Test ID | Vulnerability         | Severity | Status |
| ------- | --------------------- | -------- | ------ |
| PT-01   | CSP Header Not Set    | Medium   | Fail   |
| PT-02   | Broken Access Control | High     | Pass   |

> **Note:** CSP headers should be implemented to mitigate XSS and injection attacks.

---

## Conclusion

The Hotel Management System passed all functional tests after bug fixes and retesting. Core features are stable and validated. Minor security improvements are recommended to strengthen protection against common web vulnerabilities.

