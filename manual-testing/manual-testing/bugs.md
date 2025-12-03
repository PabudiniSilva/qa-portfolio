# Bug Reports – Demo Banking App (Applitools Demo)

## 🐞 Bug 001 – Login Button Does Not Show Error for Blank Fields
**Severity:** Medium  
**Priority:** High  

### Steps to Reproduce:
1. Navigate to https://demo.applitools.com  
2. Keep username field empty  
3. Keep password field empty  
4. Click on Login

### Expected Result:
User should see an error message such as “Fields cannot be empty”.

### Actual Result:
Login button accepts click without showing any validation message.

### Attachment:
N/A (Manual Testing)

---

## 🐞 Bug 002 – Password Field Allows Copy–Paste
**Severity:** Low  
**Priority:** Medium  

### Steps to Reproduce:
1. Go to login page  
2. Enter any text into password field  
3. Try copying and pasting text from the password field

### Expected Result:
Password fields normally block copy–paste for security reasons.

### Actual Result:
Password text can be copied and pasted.

---

## 🐞 Bug 003 – Dashboard Chart Overlaps Text on Smaller Screens
**Severity:** Medium  
**Priority:** Medium  

### Steps to Reproduce:
1. Log in with valid credentials  
2. Resize browser window to smaller width  
3. Observe chart and label positions

### Expected Result:
Charts and labels should resize properly.

### Actual Result:
Charts overlap with labels on smaller window sizes.

### Attachment:
N/A
