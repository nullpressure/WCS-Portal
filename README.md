# WCS-Portal
WCS Employee Portal Sign in Documentation

-----
## User Story

> **As a** WCS Employee,
> **I want** to Log-In on the Sign In page with my Work Email and Password  **so that** I can access the Employee Portal.

Additionally:
> **As an** IT Administrator for WCS Employee Accounts,
> **I want** the Employee Portal to use our existing Account credentials for access **so that** I can manage access and support users, while maintaining data security and access control.

### Acceptance Criteria

1. Input for Email must follow format "username@WCS.com" (i.e. regex `\S+@WCS.com$`). Thus, if input for Email does not follow this format, an error is displayed.
2. Invalid credentials of the right format should throw a generic error, but the error must not specify if username or password is wrong.
3. User Input for Password Entry Field must be obfuscated.
4. [Page Background](https://www.wcstexas.com/wp-content/uploads/2020/11/Locomotive-and-Cask-1-scaled.jpg) from Media Kit
5. [WCS Logo](https://www.wcstexas.com/wp-content/uploads/2020/09/Waste-Control-Specialists-logo.png) from Media Kit
6. Email and Password fields should be in a Sign-In node that is left-center on the page, with a white background. WCS Logo should be center-top of this node
7. Login button should be White text with a SlateBlue background color, bottom-right of the Sign-In Node

Please also consider (Additional Acceptance Criteria for IT Administrator):
1. More than 3 consecutive failed attempts for an Email should lock the account and notify the Administrator. 
2. An Administrator can create accounts for new Employees and can trigger a password reset.
3. Synchronise credentials with an existing database (e.g. WCS.com Email, ActiveDirectory, or other SSO)

### Resources:
* [WCS Media Kit](https://www.wcstexas.com/media-kit/)
