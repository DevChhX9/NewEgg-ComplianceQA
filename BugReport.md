

## BR01: Cookie Consent Not Displayed on First Visit
- **Page:** Homepage (incognito mode)
- **Severity:** Medium
- **Issue:** Cookie banner does not appear immediately on initial visit
- **Expected Behavior:** A cookie consent popup should appear in compliance with GDPR
- **Recommendation:** Ensure visibility of cookie banner for all first-time users

## BR02: Email Field Accepts Invalid Format
- **Page:** Signup Form
- **Severity:** Low
- **Issue:** Email field allows improperly formatted entries until submission
- **Expected Behavior:** Real-time validation should flag invalid formats
- **Recommendation:** Implement inline validation to reduce submission errors

## BR03: Privacy Policy Access is Not Prominent
- **Page:** Global Footer
- **Severity:** Low
- **Issue:** Privacy policy link is only available in the footer
- **Expected Behavior:** Privacy links should be more accessible during signup/login
- **Recommendation:** Add policy links near input forms or during account registration

## BR04: Password Visibility Toggle Lacks Timeout
- **Page:** Login/Signup Forms
- **Severity:** Medium
- **Issue:** Toggle icon reveals password without auto-hiding
- **Expected Behavior:** Password should auto-conceal after a short period to improve security
- **Recommendation:** Implement timeout functionality to reduce risk of shoulder-surfing

---
These reports were documented to simulate industry-standard bug tracking using a simplified Jira-style structure. All tests were conducted on public-facing UI elements only.
