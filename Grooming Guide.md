# Grooming Guide
**This document is intended to be a collaborative, living guide, to help the team progress at grooming stories until they are sprint ready.**

## Grooming Steps: 
- Read the business request/requirements/"the what".
- Understand problem and clarify scope.
- Confirm technical design is still sound from context of story.
- Confirm all Technical todos to accomplish, "the how", are present.
- Get team okay (including product).
- Estimate story effort.

## Grooming Considerations:
#### QA:
- How much QA effort is there?
- Environments:
    - Will testing change between the lower environments and prod?
- Do we want:
    - Unit tests.
    - Itegration tests.
    - Automation (Regression tests).

#### LMA:
- Alerts
- Reports
- Dashboards

#### Org Requests:
- Access/Permissions.
- White-listing.

#### Performance:
- Are there performance requirements?
- 
- What impact to performance do we anticipate? (Code||DB)
    - Do we need to conduct research / load testing to determine expected impact?
- What requirements do we need to add for performance metrics?

#### Definition of Done:
- Acceptance Criteria:
    - Happy/Sad path scenario(s)
- Other ideas:
    - LMA?
    - QA Automation Complete?

#### Documentation:
- Is there architectural significance?
    - Just like updating a house, if it is something that you would need a permit for, it is "significant".
    - If you are just changing the paint color, it isn't "significant".

#### Team Dependencies:
- Other Teams:
    - Who are we dependent on?
    - How are we dependent on them?
    - When will they be ready to release?
        - Is there a release order?

#### Are All Necessary Requirements Present:
- Api documentation.
- Configuration keys.
- Names (for anything).

#### Security:
- Any security concerns?

#### Compliance:
- Any compliance concerns?

#### Estimating:
- When the team estimates a given story as a 5, take a minute to think ifbreaking up the story is possible and more ideal.
- When the team estimates a given story above a 5, definitely break the story up into smaller pieces.
    - Why should we?  
    - How can we?



## Story Composition:
#### Story Creation:
- A well defined story has a clear scope that allows for testing with little to no dependencies.
- Compose story scope as small as possible.
- Story requirement boundary examples:
    - a story per flow.
    - a story per service (per repo).
    - a story per module.
    - a story per class.



### Story Components:
#### Summary:
- High level description on why the business wants the given software change.

#### Todo:
- Checklist of tasks for the developer to complete.
    - Include any details necessary to complete the task.

#### Repos & Dependencies:
- List the repos modified as part of the given story.
- List dependencies or any notes relevant to the release of this story.

#### Acceptance Criteria:
- Functional Requirements.

#### Subtasks:
- Do some todo's in the description make more sense as a sub-task?