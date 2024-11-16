# BEFIT- A health-related service platform.
![](https://github.com/HeyTaffazul/Code-Pioneers_057/blob/main/images/Screenshot%202024-11-16%20132628.png)
## Objective

The goal of this testing project is to evaluate the **functionality**, **performance**, and **usability** of the **BEFIT** website hosted at [Link]. This testing focuses on ensuring that the website works as expected, navigates smoothly, and provides a user-friendly experience.

---

## Table of Contents

- [Test Plan Overview](#test-plan-overview)
- [Scope of Testing](#scope-of-testing)
- [Test Criteria](#test-criteria)
- [Test Strategy](#test-strategy)
- [Deliverables](#deliverables)
- [Resources Required](#resources-required)
- [Test Execution Summary](#test-execution-summary)
- [Bug Report](#bug-report)
- [Recommendations](#recommendations)

---

## Test Plan Overview

**Objective:**  
To evaluate the functionality, performance, and usability of the **BEFIT** website, ensuring the site operates smoothly across different browsers and devices.

**Scope:**  
The testing will focus on **Functional Testing** and **Usability Testing**.

**Testing Areas:**  
- Website navigation  
- Login/Signup processes  
- Information display  
- Overall user experience  
- Accessibility

**Test Type:**  
- **Manual Testing**:  
  - **Functional Testing**: Verifying that the website’s features function as expected.  
  - **Usability Testing**: Evaluating the ease of navigation, clarity of product information, and accessibility.

**Tools Used:**  
- Browser Developer Tools  
- Figma (for wireframing)  
- Google Docs/Sheets (for documentation)  
- Trello/Jira (for defect tracking)

**Testing Environment:**  
- Desktop and Mobile Browsers (Chrome, Firefox, Edge)

**Test Execution Date:**  
12/10/2024 to 16/11/2024

**Approved By:**  
Anjali Shaw

**Tester:**  
Taffazul Ansari

---

## Scope of Testing

### Functional Testing
Ensures the core features of the website work correctly:
- **Link Navigation**: Verifying all links lead to the correct pages and are not broken.
- **Login/Signup**: Validating both correct and incorrect login/signup scenarios.
- **Services Information Display**: Ensuring accurate and formatted service details.
- **Data Entry and Verification**: Testing form data entry and validation.

### Usability Testing
Focuses on the user’s ability to interact with the website:
- **Navigation Ease**: Testing whether the website’s navigation is intuitive.
- **Services Information Accessibility**: Ensuring text readability and visual clarity.
- **Responsive Design**: Verifying that the website adjusts across devices.
- **Browser Compatibility**: Ensuring consistent behavior across major browsers.

---

## Test Criteria

### Pass Criteria:
- All functional test cases pass successfully.
- Usability testing yields positive feedback with no significant hindrances to user experience.

### Fail Criteria:
- Critical navigation problems (e.g., broken links).
- Functional failures (e.g., login/signup not returning results).
- Usability problems (e.g., unreadable text, non-responsive design).

---

## Test Strategy

### Functional Testing:
1. **Verify Link Navigation**:  
   - Test all links across the homepage and internal pages to ensure correct redirection without 404 errors.
  
2. **Test Login/Signup Functionality**:  
   - Test login/signup with both valid and invalid credentials to ensure proper handling of all scenarios.

3. **Services Information Display**:  
   - Verify if service information such as images, descriptions, and prices are accurate and correctly displayed.

4. **Data Entry and Verification**:  
   - Add new data (such as filling out forms) and check if it is stored and displayed properly on the website.

### Usability Testing:
1. **Navigation Ease**:  
   - Evaluate if the website’s navigation is user-friendly. Are menus labeled clearly? Can users find content effortlessly?

2. **Services Information Accessibility**:  
   - Ensure service details are accessible and easy to read, focusing on text size, contrast, and font clarity.

3. **Responsive Design**:  
   - Verify that the website is responsive across mobile, tablet, and desktop devices, maintaining usability and consistency.

4. **Browser Compatibility**:  
   - Test the website’s performance across major browsers such as Chrome, Firefox, Edge, and Safari.

---

## Deliverables

- **Test Cases**: Documented scenarios for both functional and usability testing.
- **Test Summary Report**: Overview of test results, including pass/fail statuses.
- **Bug Reports**: Detailed logs of any defects found during testing.
- **Feedback and Suggestions**: Recommendations to enhance the website’s usability and functionality.

---

## Resources Required

- **Hardware**: Devices (mobile, tablet, desktop) for testing.
- **Software**: Browsers (Chrome, Firefox, Edge, Safari), tools for capturing screenshots/videos (Snipping Tool).
- **Access to Website**: Ensure testers have access to the site for performing the tests.

---

## Test Execution Summary

**Total Test Cases**: 66  
**Passed**: 59  
**Failed**: 7  
**Critical Bugs**: None  
**Minor Bugs**: 7  

---

## Bug Report

| Bug ID | Module           | Test Case ID   | Scenario                               | Description                                          | Expected Result                                  | Actual Result                             | Severity | Defects    |
|--------|------------------|---------------|----------------------------------------|------------------------------------------------------|-------------------------------------------------|--------------------------------------------|----------|------------|
| B-001  | Login/Signup     | TC_LS_004     | Failed Signup with Invalid Input       | Signup with incorrect email format.                 | Error message indicating invalid input.         | Error message unclear: "Invalid email format." | Minor    | DEF_001    |
| B-002  | Activity Tracker | TC_AT_004     | View Past Week's Activity              | Verifying past week's activity display.              | Activity displayed correctly.                    | Activity data not displayed.                | Minor    | None       |
| B-003  | Activity Tracker | TC_AT_005     | View Upcoming Week's Activity          | Verifying upcoming week's activity display.          | Activity displayed correctly.                    | Activity data not displayed.                | Minor    | None       |
| B-004  | Mental Wellness  | TC_MW_004     | Personalized Recommendations           | Recommendations based on mental wellness history.    | Accurate and personalized recommendations.       | Recommendations not tailored to user’s progress. | Minor    | None       |
| B-005  | Mental Wellness  | TC_MW_005     | Progress Tracking                      | Verifying wellness progress tracking.                | Accurate tracking of progress.                   | Progress tracking not functioning.         | Minor    | None       |
| B-006  | Personal Training| TC_PT_005     | Trainer Interaction                    | Verify ability to interact with a personal trainer.  | Messages are sent and consultations are scheduled. | Messages are sent and consultations are scheduled. | Minor    | DEF_002    |
| B-007  | Personal Training| TC_PT_009     | Easy Progress Tracking                 | Verify easy tracking of workout progress.            | Progress tracking is easy and intuitive.         | Progress tracking is easy and intuitive.     | Minor    | None       |

---

## Recommendations

1. **Login/Signup**:  
   Enhance input validation and improve error messages for better user understanding.

2. **Activity Tracker**:  
   Fix data-fetching logic for past and upcoming activities to ensure consistency.

3. **Mental Wellness**:  
   Improve algorithms for more accurate personalized recommendations and progress tracking.

4. **Nutrition**:  
   Align nutrition suggestions with user preferences to avoid irrelevant plans.

5. **Personal Training**:  
   Investigate and resolve intermittent booking failures for certain time slots.

---

## Conclusion

The **BEFIT** website has undergone extensive testing for both functionality and usability. Most core features passed the tests, although some minor bugs were identified, particularly with the **Login/Signup**, **Activity Tracker**, **Mental Wellness**, and **Personal Training** modules. Addressing the identified issues will significantly enhance the user experience and functionality of the platform.

By following the recommendations outlined, **BEFIT** can ensure that its website meets the highest standards of usability, performance, and functionality.
