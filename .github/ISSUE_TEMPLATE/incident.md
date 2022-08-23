---
name: Incident
about: Incident for under 8 people team
title: ''
labels: 'incident'
assignees: ''

---

## How to report incident
1. Attach "Video of incident"
1. "Submit new issue"
1. Start voice call on slack with biz members and engineers
1. Thank you!!

## How to resolve the incident
1. Join to slack call room (should be in the room until resolve incident, even if we have nothing to talk) / 2min
1. Hearing from the first discoverer
1. Decide this is incident or not. (If one or more yes, then this problem is an incident) / 2min
    - [ ] Do we think more than 50% of users be affected?: TODO(y/n)
    - [ ] Is our data corrupting?: TODO(y/n)
    - [ ] Are we under attack unprotected areas by malicious people?: TODO(y/n)
1. Decide role / 1min
    - [ ] Investigator(should be Engineer, 1 or more person): TODO
    - [ ] Communicator(1 person): TODO
    - [ ] Recorder(1 person): TODO
1. Announce about incident and comunicator to stakeholder
    - [ ] ....(send email or pubish news or...
1. Start investigating and finishing first aid
    - [ ] problem
    - [ ] firstaid
    - Investigator comment all information and progress to this issue
    - Investigator's task:
        - [ ] firstaid
        - [ ] Research when start this problem and comment to this issue
        - [ ] Research haw many users affected by thsi problem and comment to this issue
    - Recorder organize situation and update "Record" section on this issue
        - Timeline section should be include every information to retrospect our workflow than just in template
    - Communicator informs interested parties of the situation(Take care of all non-investigation tasks so investigators can focus on their investigation)
1. Arrange 2 hours meetings for postmortem
    - [ ] Invite all people concerned on Google Calendar
1. Finishing
    - [ ] Announce resolving this incident
    - [ ] Remove "incident" label
    - [ ] Put "incident-improvement" label
1. Close slack call

## Problemt 
### Video of incidet (MUST attach)



## Record
### Timeline(UTC)
- xx/xx xx:xx: Trigger this incident (TODO: merged something, or change data or ...)
- xx/xx xx:xx: Start this incident
- xx/xx xx:xx: Find this incident by (User, Staff, ...)
- xx/xx xx:xx: Know this incident by @
- xx/xx xx:xx: Create this issue by @
- xx/xx xx:xx: Start slack call by @
- xx/xx xx:xx: Start investigating by @, @, ..
- xx/xx xx:xx: Start communication with users by @
- xx/xx xx:xx: Find root couse by @
- xx/xx xx:xx: Start first aiding by @, @, ...
- xx/xx xx:xx: Finish first aid 
- xx/xx xx:xx: Arrange postmortem
- xx/xx xx:xx: Finish slack call
- xx/xx xx:xx: ...


### Where is bug?
- TODO

### First aid
- TODO

### How many people was affected?
- TODO


### Postmortem
#### Datetime(UTC)
xx/xx xx:xx -  2 hours

#### Attendees
- xxx

#### Agenda and minutes
##### Starting (20min)
- [ ] Understand purpose and rules of postmortem (5min)
    - Improve our system
    - Improve our workflow
    - DON'T pursue liability (MUST protect psychological safety of everyone, let rulekeeper to know if you feel be broke psychological safety)
    - DON'T create action items to "be careful" or "do your best" (MUST upadte code or issue template or schedule)
    - We can improve ourselvs :+1:
- [ ] Share agenda for today (2min)
    - About good point of us
    - About root problem (Brainstormng and issue creation)
    - About our workflow (Brainstormng and issue creation)
    - About our incident mode (Brainstormng and issue creation)
    - Closing to improve and report to sakeholders
- [ ] Share summary and timeline and update (10min)
- Decide role (1min)
    - [ ] Facilitator
    - [ ] Timekeeper (or Facilitator do this role)
    - [ ] Writer
    - [ ] Rulekeeper (or Writer do this role)
        - Check all discussion and interupt to obey rules.
- [ ] Share screen by Writer (0min)

##### Listup good point of us about this incident (10min)
- ...TODO...



##### Root problem / We finished only firstaid, how to resolve it permanently? (40min)
###### Brainstorming (20min)
List up any idea
*DON'T pursue liability (MUST protect psychological safety of everyone)*
- ...TODO...



###### Discuss and Create action items and issues (10min)
*DON'T create action items to "be careful" or "do your best" (MUST upadte code or issue template or schedule)*
- [ ] ...TODO...



##### Workflow problem / How to avoid incident something like this permanently? (40min)
###### Brainstorming (20min)
List up any idea
*DON'T pursue liability (MUST protect psychological safety of everyone)*
- ...TODO...



###### Discuss and create action items and issues (10min)
*DON'T create action items to "be careful" or "do your best" (MUST upadte code or issue template or schedule)*
- [ ] ...TODO...



##### Incident mode / How can future incidents be done first aid in half of this incident time? (40min)
###### Brainstorming (20min)
List up any idea
*DON'T pursue liability (MUST protect psychological safety of everyone)*
- ...TODO...



###### Discuss and create action items and issues (10min)
*DON'T create action items to "be careful" or "do your best" (MUST upadte code or issue template or schedule)*
- [ ] ...TODO...


##### Closing (10min)
- [ ] Create weekly checking process to resolve all checkbox in this issue.
- [ ] Update incident issue template.
- [ ] Let manager to know if you feel be broke psychological safety.
- [ ] Output pdf of this issue and send it to stakeholders.
