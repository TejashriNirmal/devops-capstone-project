---
name: User Story
about: A template to write well-formatted user stories
title: ''
labels: ''
assignees: ''

---

**As a** user  
**I need** to log in to the application  
**So that** I can access my personal dashboard  
      
### Details and Assumptions
* The user must have an existing account.
* The login page will have fields for username and password.

### Acceptance Criteria     
```gherkin
Given the user is on the login page  
When the user enters valid credentials and clicks "Login"  
Then the user should be redirected to their personal dashboard.
