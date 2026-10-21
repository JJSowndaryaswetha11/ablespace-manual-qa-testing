# AbleSpace Manual QA Testing

## 1. Project Overview

This repository contains documentation of manual QA testing performed on the AbleSpace staging application as part of a QA testing assignment.

**Application URL:** https://staging.ablespace.io/

**Testing Type:** Manual Software Testing

## 2. Objectives

- Validate the functionality of key application workflows.
- Identify and document reproducible defects.
- Verify input validation and error handling.
- Execute detailed test cases and record actual results.
- Evaluate responsive layouts across different screen sizes.
- Check application behavior across browsers and the mobile application.
- Summarize testing coverage, findings, and limitations.

## 3. Scope of Testing

The following application features and testing techniques were covered:

### Functional Testing
- Account creation and email verification
- Student management
- Goal configuration and data tracking
- Service time calculations and tracking
- Accommodation management
- Worksheets and notes
- Session and data management
- Student attendance and IEO file upload

### Testing Techniques
- Positive testing
- Negative testing
- Input validation testing
- Boundary Value Analysis (BVA)
- Exploratory testing
- Detailed test case execution
- Defect identification and reporting

### Compatibility and Responsive Testing
- Web application testing using Google Chrome
- Web application testing using Microsoft Edge
- AbleSpace mobile application testing
- iPad Mini responsive emulation using Chrome DevTools
- iPad Pro responsive emulation using Chrome DevTools (testing status to be updated)

## 4. Test Environments

| Environment | Testing Details |
|---|---|
| Google Chrome | Web application testing |
| Microsoft Edge | Web application testing |
| AbleSpace Mobile App | Mobile functionality testing |
| iPad Mini Emulation | Responsive UI testing using Chrome DevTools |
| iPad Pro Emulation | Responsive UI testing; coverage to be updated |

Browser versions, device details, and viewport dimensions will be documented where verified. Not every workflow was tested in every environment.

## 5. Testing Approach

Testing was performed manually by interacting with the application, entering valid and invalid inputs, verifying expected behavior, and observing actual results.

Boundary Value Analysis was applied to the file upload limit. The application was tested with 5 files at the stated maximum and 6 files above the maximum.

Identified issues were evaluated based on their observed impact and reproducibility. Findings were recorded for further review.

## 6. Repository Contents

The following documents will be maintained in this repository:

- **Exploratory Testing:** Important scenarios explored and their observed results.
- **Detailed Test Cases:** Test steps, expected results, actual results, and execution status.
- **Bug Reports:** Reproducible defects, severity, priority, reproduction steps, and evidence.
- **Compatibility Testing:** Results across browsers, the mobile application, and responsive screen sizes.
- **Test Summary:** Overall coverage, key findings, limitations, and recommended next steps.

## 7. Limitations

- Not all application workflows were tested in every environment.
- Some features requiring a premium subscription or free trial were not tested.
- Browser and device details will be included only when verified.
- Any untested functionality and known limitations will be documented in the final test summary.

## 8. Disclaimer

This repository is intended for QA testing and portfolio documentation purposes. Testing observations reflect the behavior seen during the recorded test sessions and do not represent a guarantee of complete application coverage.
