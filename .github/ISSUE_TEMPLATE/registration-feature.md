---
name: Registration Feature
about: Fix this bug
title: ''
labels: bug
assignees: NekrosJ

---

**As a** new user  
**I need** to be able to create an account on the website  
**So that** I can access members-only features and track my orders

### Details and Assumptions
* The website currently does not support user registration.
* Users will need to provide their email, create a password, and confirm the password.
* Email verification is required to activate the account.

### Acceptance Criteria
```gherkin
Given I am on the homepage
When I click on the "Register" button
Then I should be taken to the registration form
