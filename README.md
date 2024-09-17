## LEARNING GIT CHERRY PICK
## <h1>This branch use to learning git cherry pick</h1>

### Cherry pick is used to pick some commits or features you have done before.
### For example: You've finished 5 features, but your customer just want to use 3 feature of it (ex: 2, 2, 5).

### Using git cherry pick for this situation:
### Check commits: git log --oneline

### Choose your feature commit you've done:
### git cherry-pick "commit hash feature 2" "commit hash feature 3" "commit hash feature 5"

### Notice: You don't need to write "" to cover your commit hash, just use the string seperately, for example:

#### git cherry-pick hash123 hash456 hash789