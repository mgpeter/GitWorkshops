---

theme : "night"
transition: "slide"

---

# GIT Workshops
![](2017-04-11-13-49-57.png)

---

# Agenda
![](2017-04-11-17-56-33.png)

---

# Branching models

---

## Mainline
![Mainline](2017-04-11-13-54-35.png)

---

## Cascade
![Cascade](2017-04-11-13-54-52.png)

---

## Short lived feature branches
![Short lived feature branches](2017-04-11-13-57-07.png)

---

## Continuos delivery
![Continuous Delivery](2017-04-11-13-55-19.png)

---

## gitflow
![](2017-04-11-16-31-05.png)

*successful git branching model*

---

# Common issues

---

## conflicts on dev branch

```
git push origin master
```

```
error: failed to push some refs to '/path/to/repo.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Merge the remote changes (e.g. 'git pull')
hint: before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
```

---

## automatic merges 
![](2017-04-11-14-12-19.png)

---

![](2017-04-11-17-58-08.png)

---

# Command line

---

## Three Rings for the Elven-kings under the sky,

```
git fetch
```

```
git pull
```

```
git checkout existing-branch
```

---

## Seven for the Dwarf-lords in their halls of stone,

```
git checkout -b new-branch
```

```
git add .
```

```
git commit
```

```
git checkout dev && git pull 
```

```
git checkout new-branch
```

```
git merge dev
```

```
git push
```
---

![](2017-04-11-17-50-38.png)

---

## One for the Dark Lord on his dark throne


```
git rebase -i HEAD~5
```

*In the Land of Mordor where the Shadows lie,*

*Squash last 5 commits in the current branch...*

---

![](2017-04-11-17-12-03.png)

```
git pull --rebase origin master
```

---

# 🔨
## Practical example

*http://learngitbranching.js.org*

```
level intro1
level intro2
level intro3
level intro4
```

---

# ☕

Time for a break

---

# From DEV to PRODUCTION

*How deployments and release strategy depend on git workflow?*

---

# Deployments to DEV / QA / UAT / PROD

*Merging and minimizing conflicts matters...*

---

# Pull requests

---

![](2017-04-11-17-27-57.png)

*feature branch pull requests*

---

![](2017-04-11-17-29-36.png)

*pull requests in **gitflow** do work the same way*

---

# 🔨
## providing changes via pull requests

*Preparing code with **rebase** or **merge** from main branch*

*Creating a pull request*

*Review, fix, click on **Merge***

---

# 🔨
## Releasing to QA / UAT / PROD via Pull Requests

*Prepare a pull request*

*Automatically generate release notes*

*Review the changes*

*Merge and deploy*

---

# Git commit messages

![](2017-04-11-17-54-05.png)

---

# Thanks for listening

*- Peter*

---