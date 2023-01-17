**Ticket:** [URL of the ticket]

## Description:
[Short paragraph describing what was fixed, added, or changed. Give some context such as: What problem is this addressing? What prompted this work?]

## Solution:
[Describe what this code does. If applicable, talk about other approaches you considered and why you chose this one]
[Add screenshots if applicable!]

## Customer Impact:
[If this change is behind a feature flag/toggle or not a new feature, you may opt to skip this section.]
[Short paragraph explaining how the customer will be impacted by this change. Try answering questions like: What will they see or experience? Will anything they experience cause concern, anxiety, or mistrust in the platform? What can we do to eliminate those concerns?]

## QA Testing Guidelines:
[Explain in simple terms how to test this branch, if applicable]

Checklist:

Minimally check off the following to indicate you've read & considered them. Add notes as appropriate.

- [ ] [Specs] Do you have unit/feature tests? Is code coverage sufficient?

- [ ] [Feature flags] Are the changes behind a feature flag? (If applicable)

- [ ] [Docs] Is there any documentation needed? (Tooltips, Help Article links, etc.)

- [ ] [Security] Did you add or edit a controller endpoint?

  - [ ] If so, are you using scoped finders & authorizing with pundit appropriately?

- [ ] [Monitoring] Can we detect and troubleshoot performance issues or bugs?

  - [ ] Are there timings for slow operations? Is app state logged for failures?

  - [ ] Do we need to add new Datadog monitors, graphs, or entire dashboards?
