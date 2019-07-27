## Git Question A (40% credit):

You have committed and pushed a bad change to your git repo.  How can you fix it (give exact command), without destroying history, since others might have pulled your bad change and based their changes on yours?  What would this command do?

## Git Question B (30% credit):

How do you delete a local branch after completing work on it.  How would you delete a remote branch?

## Git Question C (30% credit):

What is the difference between "cloning" and "forking" a repository?  Why would you use one or the other?

A:
git log --oneline
git revert <unwanted commit hash>

B:
git branch -d 
git push <name> --delete <branch>

C:
While both copy repositories, fork is generally more collaborative back to the original projct and clone is less so; any commits would need to be explicitly invited to do so.

