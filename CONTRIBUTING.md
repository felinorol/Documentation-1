# Contributing to Documentation

## Issue Contributions

When opening new issues or commenting on existing issues on this repository please make sure discussions are related to concrete technical issues with the WPC(Workshop of Projects for Companies).

## Code Contributions

This document will guide you through the contribution process.

### Step 1: Fork

Fork the project [on GitHub](https://github.com/Code-Work/Documentation) and check out your
copy locally.

```sh
$ git clone git@github.com:username/Documentation.git
$ cd Documentation
$ git remote add upstream https://github.com/Code-Work/Documentation.git
```

> UPSTREAM is a common name to original remote repositories

### Syncing a fork

```sh
$ git fetch upstream
$ git checkout master
$ git merge upstream/master
```

For developing new features, add documents, the 'master' branch should be pulled and built upon.

### Step 2: Branch

Create a branch and start coding:

```sh
$ git checkout -b my-branch -t origin/master
```
### Step 3: Commit

Make sure git knows your name and email address:

```sh
$ git config --global user.name "My Name"
$ git config --global user.email "email@example.com"
```

Writing good commit logs is important. A commit log should describe what
changed and why. Follow these guidelines when writing one:

1. Contain a short description of the change prefixed with the name of the changed.
- ADD (Add some content or feature)
- FIX (Fix some content or feature)
- REMOVE (Remove some content or feature)

A good commit log can look something like this:

```txt
  ADD MY-FILE
```

or

```txt
  ADD MENU TO HOME SCREEN
```

### Step 6: Push

```sh
$ git push origin my-branch
```
Go to https://github.com/yourusername/Documentation and select your branch.
Click the 'Pull Request' button and fill out the form.

