
### Useful Git Commands

- `git reflog`

    Is a command in Git that shows a log of all the changes made to the local repository's references. This log includes information about all the branch updates, branch creations, branch deletions, and tag operations that have been performed on the local repository.

    The git reflog command is useful for tracking the history of changes to the local repository's references. It can help you see which branches and tags were created, deleted, or updated, and when these changes were made. This information can be useful for recovering lost or deleted branches, or for tracking the history of changes to the local repository.

- `git rebase` 
    
    Is a command in Git that is used to move a branch to a new base commit. The git rebase command is useful for rewriting the project history by creating new commits for existing commits. It can be used to combine multiple commits into one commit, or to split one commit into multiple commits. It can also be used to change the base commit of a branch, or to move a branch to a new base commit.

- `git reset --sort HEAD~1`

    This command will reset the HEAD to the last commit. This is useful when you want to undo a commit but keep the changes.

- `git rest --hard HEAD~1`

    This command will reset the HEAD to the last commit and delete the changes. This is useful when you want to undo a commit and delete the changes.

- `git push <remote> <local-branch-name>:<remote-branch-name>`

    This command will push a local branch to a remote branch. This is useful when you want to push a local branch to a remote branch with a different name.

- `git push --force <remote> <commit-code>:<remote-branch-name>`
        
    This command will force push a commit to a remote branch. This is useful when you want to force push a commit to a remote branch.