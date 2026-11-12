CodeAlpha Secure Coding Review

Project Overview

This project involves a manual security review of a Python Flask login application as part of CodeAlpha Internship Task 3.

Objective

To examine the application's source code, identify potential security weaknesses, and recommend appropriate remediation measures.

Review Method

The review was conducted through manual source-code inspection. No automated security scanner or penetration testing was performed.

Key Findings

- Hard-coded login credentials.
- Weak password choice and lack of password hashing.
- No visible login rate-limiting mechanism.
- Login form field mismatch causing a functional issue.
- CSRF protection not visible in the reviewed form.

Recommendations

- Store credentials securely and outside source code.
- Use strong passwords and secure password hashing.
- Implement login rate limiting.
- Correct the form field mismatch.
- Review and implement appropriate CSRF protection.

Technologies

- Python
- Flask
- HTML

Project Contents

- Application source code
- Login page
- Requirements file
- Dockerfile
- Security review report

Scope and Limitations

This review was limited to the supplied source files. Findings about controls not visible in those files require further verification. 
