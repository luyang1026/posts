---
layout: post
title: Git Cherry-Pick
tags: [git]
---
### When You Need to Make a Commit in Tow Branches

```
A--B--C--D--F  ← master ← HEAD
      \--E  ← v1-release
```
Now commit F with a bugfix must be applied to v1-release branch.

### How to Make a Commit in Tow Branches
```bash
git checkout v1-release
git cherry-pick F
```
<span style="background:#e6d2d2; padding:0 2px">cherry-pick</span> command applies changes made by a specific commit to current branch, creating a new commit.

```
A--B--C--D--F  ← master ← HEAD
      \--E--G  ← v1-release
```
Commit G introduces same changes as F.

