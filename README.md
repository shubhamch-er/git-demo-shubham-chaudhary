# Git Demo by `Shubham Chaudhary`

### Command explored and used

1. `git config --list` > It show the git configrations like Email, Username and other important stuff. If this is used inside the git directory it shows some extra configs like remote.origin.url etc.

1. `git init` > Initialize the git directory
1. `tree .git` > `tree` must be installed in ubuntu, it shows the folder structure in tree form
1. `git status` > checks the working status locally
1. `git add <fileName>` > Add the file to staging area
1. `git commit -m "Any meaningful message"` > Commits the changes
1. `git remote add origin <repo-url>` > Adds remote origin to local repo
1. `git push` > Initially shows error if upstream is not set. So set upstream using below command
1. `git push --set-upstream master` > Sets upstream
1. `git restore --staged <fileName>` > restore the file from staging area.
1. `git rm --cached <fileName>` > removes the file from staging area.
1. `git log` > Logs all the commits
1. `git diff <commitId1> <commitId2>` > shows working difference between 2 commits
1. `git checkout -b <branchName>` > creates and changes the working branch locally
1. `git push origin <branchName>` > push to mentioned branch
1. `git checkout master` > Changes working branch to master
1. `git pull` > pulls from master
1. `git merge <branchName>` > merges the current branch with mentioned branch
1. `git push` > pushes the code to remote
1. `git tag <release_version>` > creates a new tag locally
1. `git push origin <release_version>` > pushes the tag to remote.
