# Email Validator

A robust email validation tool written in Go that performs the following checks:

- **Syntax Validation**: Ensures the email follows RFC 5322 and RFC 5321 standards.

- **DNS Validation**: Verifies the domain part of the email has valid Mail Exchange (MX) records.
- **SMTP Validation**: Connects to the mail server to check if the email address exists (without sending an email).
