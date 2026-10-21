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
| iPad Pro Emulation | Responsive UI testing using Chrome DevTools |

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
## 9. Test Summary

### 1. Testing Performed
Manual testing was performed on the AbleSpace staging application to verify functional workflows, input validation, data handling, UI behavior, and responsive design. Testing covered student management, goal configuration and data tracking, Service Time, Accommodation, session management, reports, Activity History, announcements, worksheets, and calendar features. The tested environments included Google Chrome, Microsoft Edge, the AbleSpace mobile application, and iPad Mini and iPad Pro emulations.

### 2. Issues Found
Three major functional bugs were documented, along with additional UI and compatibility issues. The functional bugs involved editing newly captured data, an incorrect numeric value in Edit Session, and the Mastered status remaining after deleting a successful data record. I would prioritize the Mastered status issue because inaccurate student progress information could affect progress tracking and decision-making. Additional issues included navigation failures, layout problems, missing UI elements, and search-related behavior.

### 3. Areas Not Tested
Features requiring a paid subscription or free trial were not tested. Not every workflow was tested across every browser and device, so compatibility coverage was limited to the scenarios actually executed.

### 4. What I Would Test Next
With another one to two hours, I would retest the three functional bugs, verify that goal mastery status recalculates correctly after data changes, and perform regression testing on related student and goal workflows. I would also investigate the mobile and iPad navigation issues and test additional boundary cases and responsive layouts. These checks would help validate data accuracy and improve usability across supported environments.
