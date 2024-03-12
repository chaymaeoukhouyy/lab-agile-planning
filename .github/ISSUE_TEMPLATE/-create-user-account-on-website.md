---
name: " Create User Account on Website"
about: This user story pertains to the functionality enabling website visitors to
  create a user account
title: ''
labels: ''
assignees: ''

---

**As a** website visitor  
**I need** to be able to create an account  
**So that** I can access exclusive content and save my preferences  

### Details and Assumptions
* The user must provide a valid email address and password to create an account.
* After creating an account, the user should receive a confirmation email.

### Acceptance Criteria

```gherkin
Given I am on the website registration page
When I enter my email address and password
Then I should receive a confirmation email
```
