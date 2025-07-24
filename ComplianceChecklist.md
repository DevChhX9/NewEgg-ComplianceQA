

| Compliance Standard | Requirement | Observed Feature | Notes |
|---------------------|-------------|------------------|-------|
| GDPR | Cookie consent before tracking | Not visible on first load (incognito) | Consent banner missing or delayed |
| GDPR | Easy access to privacy rights | Link exists in footer | Could be more prominent on login/signup |
| GDPR | Right to delete or export data | Not clearly available in account settings | No clear “delete my data” option visible |
| PCI-DSS | HTTPS on checkout/payment pages | All payment steps are secure | Valid SSL observed |
| PCI-DSS | Masked card and CVV inputs | Fields use masking on input | Satisfactory input protection |
| General Security | Form validation | Some fields lack real-time validation | Email field allows bad input until submit |
| General Security | Password visibility control | Toggle works but lacks auto-hide | Could be improved for shoulder-surfing prevention |

---
This checklist is based on publicly accessible features and intended for educational demonstration of QA analysis. It helps highlight how real platforms may meet or fall short of common standards.

This analysis was documented using Jira-style formatting for test case traceability and issue tracking, demonstrating familiarity with tools such as Jira, TestRail, and Google Sheets to simulate a real QA workflow environment.
