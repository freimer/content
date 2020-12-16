# O365 - EWS - Extension

This integration enables you to manage and interact with Microsoft O365 - Exchange Online from XSOAR.

Supported authentication methods:

- Basic authentication - Fill in the UPN and password.
- OAuth2.0 (For MFA enabled accounts) -
    1. Enter a value for the UPN parameter in the integration configuration.
    2. Run the ***ews-auth-start*** command and follow the instructions.
    3. Run the ***o365-ews-test-auth*** command to verify that the authorization process was implemented correctly.