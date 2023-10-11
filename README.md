
# github-timelines

this repository should contain different kinds of branch workflows in regards to pull requests.

## Cases

### 1. Force push without similarities before PR
**Steps**
branch main~ case1 ->  push -> commit change1 -> push -> reset HEAD~1 -> commit change2 -> force push -> pr open case1->main
**Expected Outcome**
Timeline: change1, force push, change2

### 2. Rebase before PR
**Steps**
branch main~1 case2 -> push -> commit change1 -> push -> rebase main~ -> force push -> pr open case2->main


## Main branch history
readme -> create_file