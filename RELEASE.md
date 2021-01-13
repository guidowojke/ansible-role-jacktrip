# How to release
## GitFlow Documentation
* https://nvie.com/posts/a-successful-git-branching-model/
* https://jeffkreeftmeijer.com/git-flow/
* https://bitbucket.org/atlassian/jgit-flow/wiki/Home

### automated release with jgitflow-maven-plugin (Quick Release)
```
git pull --all
mvn --batch-mode jgitflow:release-start jgitflow:release-finish
```

## view git network on the command line
* `git log --pretty=oneline --graph --decorate --all`
