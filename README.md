# Course Specifications Repo

This is the **specifications repo** used in the **AIDE Deep Dive course** (also known as the AIDE Crash Course). Over the course of the session you will build up your requirements, solution, and implementation specifications here.

Its siblings are [`course-project-workspace`](https://dev.azure.com/IntelliwareDev/AI_Knowledge_Repo/_git/course-project-workspace), which holds the framework and the project configuration and is the one you clone first, and [`course-knowledge-base`](https://dev.azure.com/IntelliwareDev/AI_Knowledge_Repo/_git/course-knowledge-base), the knowledge base repo.

## Nothing is ever merged into `main`

`main` is protected, and not because something is waiting to be reviewed. **Nothing from the course is ever merged into it.** It is the clean starting point every participant clones, and it has to stay exactly as you found it so the next person — and the next run of the course — starts from the same place.

So there is no pull request to raise, no approval to wait for, and nobody reviewing your work. You cannot push to `main`, you are not meant to, and none of that is a problem to solve. **Your branch is where your work lives and stays.**

## This repo should be empty

Aside from this README, this repo should contain **no other files**. That is the expected starting state for every participant.

If you look around and find other content already here, it means the working copy is carrying someone else's work — most likely a previous run of the course. Don't delete it and don't build on top of it. Instead, start from a clean branch:

```bash
git checkout main
git pull
git checkout -b <your-unique-branch-name>
```

Pick a branch name that is unique to you, for example `jdoe/aide-deep-dive` or `aide-2026-09-jdoe`. Use the same name in all three course repos — nothing enforces it, it just means you never have to work out which branch you are on in which folder.

Normally your instructor will have taken care of this for you before the session starts, so in most cases there is nothing for you to do here.
