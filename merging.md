## Merging

### Feature or fix branch to main

Before merging from a feature or fix branch back to the main branch (e.g. `main`, `master`, `trunk`), you **must** merge any changed from the main branch into the feature or fix branch.

THe merge from the main branch to the feature branch (prior to the merge in the other direction) must be done with a _discpline_. For example, we may do this on a daily basis&mdash;that is, while working on a feature branch, the developer would merge any new changes from the main branch into the feature branch every day.

In any event, immediately prior to merging from a feature or fix branch to the main branch, a merge in the opposite direction **must** be performed, to reduce as much as possible the need to resolve conflicts when merging to the main branch.