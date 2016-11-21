#Git

* [Learn Git in 15 minutes](https://try.github.io/levels/1/challenges/1)
* [GitHub Git Cheat Sheet](https://training.github.com/kit/downloads/github-git-cheat-sheet.pdf)
* [Tower Git Cheat Sheet](https://www.git-tower.com/blog/git-cheat-sheet/)
* [Learn Git with Bitbucket Cloud](https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud)
* [Oh, shit, git!](http://ohshitgit.com/)

## FAQs

* [Generating a SSH key](https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/)
* [Adding a SSH key to Github](https://help.github.com/articles/adding-a-new-ssh-key-to-your-github-account/)

## Useful stuff


### Renaming a branch
```
git branch -m old-name new-name
git push origin :old-name new-name
```

### Deleting a branch
```
git branch -d -r origin/branch-to-delete
git push origin :branch-to-delete
```

## Reverting a change
```
git checkout :sha
git checkout -b :new-patched-branch
```
