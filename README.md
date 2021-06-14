# Git Demo by `Shubham Chaudhary`

[![Build Status](https://img.shields.io/badge/Version-1.0-orange.svg)](https://github.com/shubhamch-er/git-demo-shubham-chaudhary/releases/tag/RELEASE_v1.0)[![Build Status](https://img.shields.io/badge/-1.1-blue.svg)](https://github.com/shubhamch-er/git-demo-shubham-chaudhary/releases/tag/RELEASE_v1.1) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/shubhamch-er/git-demo-shubham-chaudhary/releases/tag/RELEASE_v1.0)

### Command explored and used

1. `git config --list` > It show the git configrations like Email, Username and other important stuff. If this is used inside the git directory it shows some extra configs like remote.origin.url etc.

1. `git init` > **Initialize** the git directory. [Read More](https://git-scm.com/docs/git-init)
1. `tree .git` > `tree` must be installed in ubuntu, it shows the folder structure in tree form. [Read More](https://manpages.ubuntu.com/manpages/xenial/man1/tree.1.html)
1. `git status` > checks the **working status** locally. [Read More](https://git-scm.com/docs/git-status)
1. `git add <fileName>` > **Add the file** to staging area. [Read More](https://git-scm.com/docs/git-add)
1. `git commit -m "Any meaningful message"` > **Commits** the changes. [Read More](https://git-scm.com/docs/git-commit)
1. `git remote add origin <repo-url>` > **Adds remote origin** to local repo. [Read More](https://git-scm.com/docs/git-remote)
1. `git push` > Initially shows **error if upstream is not set**. So set upstream using below command. [Read More](https://git-scm.com/docs/git-push)
1. `git push --set-upstream master` > **Sets upstream**.[Read More](https://git-scm.com/docs/git-push)
1. `git restore --staged <fileName>` > **restore the file from staging area**. [Read More](https://git-scm.com/docs/git-restore)
1. `git rm --cached <fileName>` > **removes the file from staging area**. [Read More](https://git-scm.com/docs/git-rm)
1. `git log` > **Logs** all the commits. [Read More](https://git-scm.com/docs/git-log)
1. `git diff <commitId1> <commitId2>` > shows **working difference** between 2 commits. [Read More](https://git-scm.com/docs/git-diff)
1. `git checkout -b <branchName>` > **creates and changes** the working branch locally. [Read More](https://git-scm.com/docs/git-checkout)
1. `git push origin <branchName>` > **push** to mentioned branch. [Read More](https://git-scm.com/docs/git-push)
1. `git checkout master` > Changes **working branch** to master. [Read More](https://git-scm.com/docs/git-checkout)
1. `git pull` > **pulls from master**. [Read More](https://git-scm.com/docs/git-pull)
1. `git merge <branchName>` > **merges** the current branch with mentioned branch. [Read More](https://git-scm.com/docs/git-merge)
1. `git push` > pushes the code to remote. [Read More](https://git-scm.com/docs/git-push)
1. `git tag <release_version>` > creates a **new tag** locally. [Read More](https://git-scm.com/docs/git-tag)
1. `git push origin <release_version>` > pushes the **tag to remote**. [Read More](https://git-scm.com/docs/git-push)
1. `git commit -am "Any Meaningful Message"` > adds and commit at the same time. `NOTE`: **Works only if the file is modified and not newly created**. [Read More](https://git-scm.com/docs/git-commit)
