# Test Cases for Demo Banking App (Applitools Demo)

## 1. Test Case: TC001 – Verify Login Page Loads
**Objective:** Ensure login page loads successfully  
**Precondition:** User has internet connection  
**Steps:**  
1. Navigate to https://demo.applitools.com  
**Expected Result:** Login page should load with username, password, and login button.

---

## 2. Test Case: TC002 – Login with Valid Credentials
**Objective:** Verify user can log in with correct details  
**Test Data:** username / password  
**Steps:**  
1. Enter valid username  
2. Enter valid password  
3. Click Login  
**Expected Result:** User should be redirected to the dashboard.

---

## 3. Test Case: TC003 – Login with Invalid Credentials
**Objective:** Verify error is shown for invalid login  
**Test Data:** Invalid username and password  
**Steps:**  
1. Enter incorrect username  
2. Enter incorrect password  
3. Click Login  
**Expected Result:** An error message should appear.

---

## 4. Test Case: TC004 – Login with Blank Fields
**Objective:** Validate system behavior when fields are empty  
**Steps:**  
1. Do not enter any username  
2. Do not enter any password  
3. Click Login  
**Expected Result:** Error message or validation warning must appear.

---

## 5. Test Case: TC005 – UI Elements Verification
**Objective:** Check presence and alignment of login fields  
**Steps:**  
1. Open login page  
**Expected Result:** Username field, password field, remember-me checkbox & login button must be visible and aligned correctly.

---

## 6. Test Case: TC006 – Dashboard Loads After Login
**Objective:** Verify dashboard UI loads correctly  
**Precondition:** User logged in successfully  
**Steps:**  
1. Log in with valid credentials  
**Expected Result:** Dashboard should show “Expenses”, “Balance”, charts etc.

---

## 7. Test Case: TC007 – Verify Remember Me Checkbox
**Objective:** Ensure checkbox works  
**Steps:**  
1. Check the “Remember Me” option  
2. Log in  
**Expected Result:** User’s session should be saved (if feature is implemented).

---

## 8. Test Case: TC008 – Password Field Security
**Objective:** Password must be hidden  
**Steps:**  
1. Type password  
**Expected Result:** Password is masked (●●● style).

---

## 9. Test Case: TC009 – Verify Browser Back Button
**Objective:** Ensure security after login  
**Steps:**  
1. Log in successfully  
2. Press browser back button  
**Expected Result:** App should not show login details or sensitive data without re-authentication.

---

## 10. Test Case: TC010 – Validate Page Title
**Objective:** Check if the website title is correct  
**Steps:**  
1. Open login page  
**Expected Result:** Title should contain “ACME Bank” or similar brand reference.
