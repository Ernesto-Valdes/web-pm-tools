

## Two Main branches


```
master
develop
```

The main branch `master` where the source code of HEAD always reflects a production-ready state.

The `develop` branch is where the source code of HEAD always reflects a state with the latest delivered development changes for the next release.



## New branch naming

Name branch with meaning. Make it easy to other developers to understand the purpose of the branck as quick as possible. These are some examples:

`fix-name`, `feature-name`, `release-name`



## Branch from right source

Always make sure to branch from proper root. Here are some typical steps to list and switch branches:


```
# git branch
# git checkout [name_of_branch]
```


## Commit everything

Commit with purpose, one commit per issue. Add tracking id to your commit (bind commit and user story).

Add a commit message describing issue. It should be short, but easy to understand for other developers and you after 3+ months.

```
# git add [file]
# git commit -m “[#id descriptive_message]”
```



## Inspect changes before commits

Make sure your commit comment actually match your code changes. Always check the pending changes before commiting.


```
# git diff
```



## Remove Personal Settings

Remove personal settings from your VC project. It will help to keep the VC clean and easy to load locally. Use the `.gitignore` file:

```
node_modules
dist
.tmp
.sass-cache
app/bower_components
```

For more info, read [gitignore docs](http://git-scm.com/docs/gitignore).


**********

## Other References
- [x] http://www.troyhunt.com/2011/05/10-commandments-of-good-source-control.html

- [x] http://blog.manishchhabra.com/2011/04/10-version-control-best-practices/

- [x] http://sethrobertson.github.io/GitBestPractices/

- [x] https://github.com/timoxley/best-practices

- [x] https://github.com/thoughtbot/guides/tree/master/best-practices

- [x] https://github.com/timoxley/best-practices

- [] http://www.rdegges.com/successful-github-development/
http://blog.endpoint.com/2014/05/git-workflows-that-work.html

[Flow](https://guides.github.com/introduction/flow/)

[Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow)

[Github Flow](http://scottchacon.com/2011/08/31/github-flow.html)

[Origin Google file](https://docs.google.com/document/d/19jKkIImsozZXb_J9r5sE05FfW1XIKt-XQFkHBpYpJZg/edit#)
