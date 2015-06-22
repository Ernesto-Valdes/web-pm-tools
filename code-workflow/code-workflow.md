## Branches

Always keep two main branches for the development process:

```
master
develop
```

The main branch `master` where the source code of HEAD always reflects a production-ready state.

The `develop` branch is where the source code of HEAD always reflects a state with the latest delivered development changes for the next release.


## Github Workflow

> GitHub Flow is a lightweight, branch-based workflow that supports teams and projects where deployments are made regularly. This are the main steps:

1. Create a branch
2. Add commits
3. Open pull request
4. Discuss and review
5. Merge and deployments

Read more on [Github workflow](https://guides.github.com/introduction/flow/).


## Branch Naming

Name new branch with meaning. Make it easy to other developers to understand the purpose of the branch. These are some examples:

`fix-name`, `feature-name`, `release-name`



## Branch from right source

Always make sure to branch from proper root. Here are some typical steps to list and switch branches:


```
# git branch
# git checkout [name_of_branch]
```


## Commit everything

Commit with purpose, one commit per issue. Add asana tracking id to your commit; this will help bind your commit and user story.

Also add a commit message describing the changes. It should be short, but easy to understand for other developers and you after 3+ months.

```
# git commit -m “[#id descriptive_message]”
```



## Inspect changes before commits

Make sure your commit comment actually match your code changes. Make sure to always check the pending changes before committing.


```
# git diff
```



## Intentionally Untracked Files

Remove personal and development settings from the project. It will help to keep the repo clean and faster to clone for new members of the team. Use the `.gitignore` file. Here is an example:


```
/* .gitignore file */
node_modules
app/bower_components
dist
.tmp
.sass-cache
personal-todo.md
```

For more info, read [gitignore docs](http://git-scm.com/docs/gitignore).




**********

## Other References

- [ ] [Github Cheat Sheet](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)

- [ ] http://www.rdegges.com/successful-github-development/
http://blog.endpoint.com/2014/05/git-workflows-that-work.html


- [ ] [Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)

- [ ] [Github Flow](http://scottchacon.com/2011/08/31/github-flow.html)

- [ ] [Origin Google file](https://docs.google.com/document/d/19jKkIImsozZXb_J9r5sE05FfW1XIKt-XQFkHBpYpJZg/edit#)

- [x] [Flow](https://guides.github.com/introduction/flow/)

- [x] http://www.troyhunt.com/2011/05/10-commandments-of-good-source-control.html

- [x] http://blog.manishchhabra.com/2011/04/10-version-control-best-practices/

- [x] http://sethrobertson.github.io/GitBestPractices/

- [x] https://github.com/timoxley/best-practices

- [x] https://github.com/thoughtbot/guides/tree/master/best-practices

- [x] https://github.com/timoxley/best-practices
