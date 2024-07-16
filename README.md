# push

Helper utilities to push code to multiple git providers. 

## Instructions

Open the `.git` folder in the root of your project and add a new `pushurl` to the `.git/config` file. 

```bash
[remote "origin"]
    url = git@provider1:user/repo.git
    fetch = +refs/heads/*:refs/remotes/origin/*
    pushurl = git@provider1:user/repo.git
    pushurl = git@provider2:user/repo.git
``` 