---
layout: post
title: Git Alias
tags: [git]
---

```bash
# alias checkout globally
git config --global alias.co checkout
# alias reset head -- filename locally
git config alias.unstage 'reset HEAD --'
```

When --global flag is set, system level config file which locate at ~/.gitconfig is written. Otherwise it will be at .git/config.
