# Checking Pull requests
By this command, you should check whether the pull request number $1 is safe to be merged into the desired place.

Use `gh` command if you need any information of the pull request.

## What does it mean to be `safe` to merge?
When I mention `safe` to merge, it means
- There is no differences of movement between the current branch and the branch that we are trying to merge to, except the branch is trying to change what it does.
- The branch trying to be merged does what it should do.

Try your best to be accurate since it can cause severe problems later on.