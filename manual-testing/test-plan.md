# Test Plan for Demo Banking App (Applitools Demo)

## 1. Introduction
This test plan is for the demo web application at https://demo.applitools.com.  
The purpose is to verify the login functionality and dashboard UI components.

## 2. Scope of Testing
### In Scope:
- Login page UI
- Login form validation
- Successful login with correct credentials
- Dashboard page loading

### Out of Scope:
- API testing
- Performance testing
- Mobile testing

## 3. Testing Approach
Manual testing will be performed using:
- Functional testing
- Positive and negative test scenarios
- UI validation
- Exploratory testing

## 4. Test Items
- Login page (Username, Password, Login button)
- Dashboard elements after login

## 5. Test Environment
- Website: https://demo.applitools.com
- Browser: Chrome latest
- OS: Windows 10/11

## 6. Test Data
Valid username: **username**  
Valid password: **password**

Invalid data: random / blank values

## 7. Acceptance Criteria
- User should be able to log in using valid credentials
- Error message must appear for invalid login
- Dashboard should load correctly after successful login

## 8. Deliverables
- Test Plan
- Test Cases
- Bug Reports

## 9. Risks & Mitigation
| Risk | Mitigation |
|------|------------|
| Application changes | Update test cases accordingly |
| Browser issues | Use stable version of Chrome |

## 10. Approval
**Prepared by:** Pabudini Silva  
**Role:** QA Intern (Student)
