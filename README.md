## LEARNING GIT
## <h1>This repository use to learning git</h1>

## GIT MERGE:
### <p>Will create a commit each merging from main branch to task branch</p>

## GIT REBASE:
### <p>Will not create a commit each merging from main branch to task branch like git merge</p>

## GIT REMOTE:
## Will create 2 or more remote: origin & release

## Run git remote add release "git repository name"

## You can named it by other name, not only "release", for example: "product", "uat", "development"

## Run git remote -v to see these 2 remote
## Run git push origin to push code to origin
## Run git push release to push code to release


## GIT BRANCH:
### Create branch: git checkout -b "branch name" or git branch "branch name"

### Switch branch: git checkout "branch name"

### Delete branch: git branch -D "branch name"
#### After delete branch, will show "was 'commit hash'"

### Restore branch by commit: git checkout -b "branch name" "commit hash"

## GIT CHERRY PICK:

### Cherry pick is used to pick some commits or features you have done before.
### For example: You've finished 5 features, but your customer just want to use 3 feature of it (ex: 2, 2, 5).

### Using git cherry pick for this situation:
### Check commits: git log --oneline

### Choose your feature commit you've done:
### git cherry-pick "commit hash feature 2" "commit hash feature 3" "commit hash feature 5"

### Notice: You don't need to write "" to cover your commit hash, just use the string seperately, for example:

#### git cherry-pick hash123 hash456 hash789


## CHANGE AUTHOR OF COMMIT:
### RUN git rebase -i <commit hash> or <HEAD~<commit index>>
### PRESS INSERT AND CHANGE ALL PICK TO EDIT
### PRESS ESC AND TYPE :wq TO SAVE CHANGES & QUIT VIM
### RUN git commit --amend --author="authorname <authorEmail>" --no-edit
### IF DON'T WANT TO USE OTHER AUTHOR, JUST USE CURRENT GIT USER OF YOUR LOCAL 
##### -> RUN git commit --amend
### RUN git rebase --continue UNTIL YOU SATISFY