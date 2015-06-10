# Version 1 - Notes

* What's this PR do?
* Where should the reviewer start?
* How should this be manually tested?
* Any background context you want to provide?
* What are the relevant tickets?
* Screenshots (if appropriate)
* Questions:
  - Is there a blog post?
  - Does the knowledge base need an update?
  - Does this add new (Python) dependencies which need to be added to chef?


# Version 2 - Sections


## Status
**READY/IN DEVELOPMENT/HOLD**


## Migrations
YES | NO


## Description
A few sentences describing the overall goals of the pull request's commits.


## Related PRs
List related PRs against other branches:

branch | PR
------ | ------
other_pr_production | [link]()
other_pr_master | [link]()


## Todos
- [ ] Tests
- [ ] Documentation


## Deploy Notes
Notes regarding deployment the contained body of work.  These should note any db migrations, etc.

## Steps to Test or Reproduce
Outline the steps to test or reproduce the PR here.

```sh
git pull --prune
git checkout <feature_branch>
bundle; script/server
```

1. Step One
2. Step Two
3. Another Step


## Impacted Areas in Application
List general components of the application that this PR will affect:

* Impact this
* Impact that
* Also impact
