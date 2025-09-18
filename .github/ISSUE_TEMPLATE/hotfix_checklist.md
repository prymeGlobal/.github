---
name: "Hotfix Checklist"
about: "Checlist for a new hotfix"
title: 'Hotfix X.Z.N checklist'
labels: admin
assignees: ''
---
Hotfix releases must have a release version of X.Y.N where X.Y is the major minor of the _previous_ release and N is the hotfix number.

E.g. The previous release was 4.5, then the first hotfix for 4.5 will be 4.5.1
Do not confuse this with the _build_ version, hotfix 4.5.1 could have build version 4.5.627.0

- [ ] Hotfix release branch (release/X.Y.N) is created from previous release branch.
- [ ] Work items in hotfix release branch tested and marked as Done.
- [ ] Release is created from hotfix release branch.
- [ ] Hotfix release branch is merged into main.
- [ ] App is published and live.
- [ ] Release notes are updated and published live.
