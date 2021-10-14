# github-workflows

This repository is intended to hold common github workflow scripts.

Each customer installation has its own branch. There is also a branch `expt` for publishing to our own ECR registry.

The workflow should be installed into a applications repository using
git-subrepo. See https://github.com/ingydotnet/git-subrepo#installation-instructions.


To copy this subrepo into an application's repository:
```
git subrepo clone git@github.com:epimorphics/github-workflows.git .github/workflows -b <branch>
```

To update this subrepo in an application's repository:
```
git subrepo pull .github/workflows
```
