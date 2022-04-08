---
name: Final Project
about: Final project template
title: ''
labels: ''
assignees: ''

---

**As a** [Service Provider]  
 **I need** [I need the service to persist the last known count]  
 **So that** [So that users don't lose track of their counts after the service is restarted.]  
   
 ### Details and Assumptions
 * [We will use a redis database]
 * [Counters will be stored as a main value pair]
   
 ### Acceptance Criteria  
   
 ```gherkin
 Given [I have incremented the counter to 2]
 When [I make a call to get the current value]
 Then [It should return 2 as the counter value]
 ```
