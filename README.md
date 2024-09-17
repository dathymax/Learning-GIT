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