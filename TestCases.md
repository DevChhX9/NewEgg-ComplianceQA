
## 1. Login and Signup

### TC01: Empty Field Validation (Signup)
- **Description:** Submit the signup form with all fields blank
- **Expected Result:** All required fields should display validation errors

### TC02: Email Format Validation
- **Description:** Enter improperly formatted emails (e.g., "test@", "user@.com")
- **Expected Result:** Field should display a real-time validation message

### TC03: Password Visibility Toggle
- **Description:** Toggle password visibility icon during input
- **Expected Result:** Password input should be securely toggled and auto-hide after inactivity (if implemented)

## 2. Checkout and Payment (PCI-DSS)

### TC04: Credit Card Field Masking
- **Description:** Enter a full 16-digit card number during checkout
- **Expected Result:** Input should display only the last four digits and apply masking

### TC05: CVV Validation
- **Description:** Enter invalid CVV values (e.g., 1 digit or 4 digits)
- **Expected Result:** Field should restrict input to 3 digits with error messages on invalid entries

### TC06: HTTPS Checkout
- **Description:** Check URL scheme during the payment process
- **Expected Result:** Checkout pages should be securely served over HTTPS

## 3. Privacy and GDPR

### TC07: Cookie Consent Banner
- **Description:** Open the homepage in an incognito window
- **Expected Result:** A cookie consent banner should appear on first load

### TC08: Privacy Policy Link Visibility
- **Description:** Locate privacy policy links across the site
- **Expected Result:** Links should be clearly accessible without excessive navigation

### TC09: Data Deletion or Export Option
- **Description:** Navigate account settings to locate data control options
- **Expected Result:** Option to delete or export user data should be present as per GDPR

## 4. General QA and Security Checks

### TC10: Form Auto-fill Handling
- **Description:** Use a browser password manager to autofill login fields
- **Expected Result:** Fields should accept input while maintaining masking and security

### TC11: Input Field Types
- **Description:** Inspect input elements on signup and login forms
- **Expected Result:** Appropriate HTML5 input types should be used (e.g., `type="email"`, `type="password"`)

### TC12: Error Messaging Clarity
- **Description:** Trigger form validation errors by submitting incorrect or empty data
- **Expected Result:** Clear and user-friendly error messages should appear to guide correction

---
These test cases simulate a real QA workflow and can be executed or documented using platforms such as Jira, TestRail, or Excel-based templates.
