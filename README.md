# Example Git Repo

This is an example git repo. 

## Master Branch

The master branch is the default branch.

Branches are useful tools when making modifications, as any commits you make
as a team don't interfere with each other. Once you're done with your feature,
you can merge it back into master.

You can also use branches for hosting on [Github Pages](https://pages.github.com/) 

## Branching
This repo features an additional branch called examplebranch.

To make a branch type `git branch BRANCHNAME`.
That will make a branch called BRANCHNAME

Then changes you make will be isolated to that branch.

Once you're done, you can merge your changes back into the master branch by
typing `git checkout master` and `git merge BRANCHNAME`

Changes made to files both in the master, and in a branch are usually automatically merged,
but you can see [here](https://help.github.com/articles/resolving-a-merge-conflict-from-the-command-line/) for instructions on how to reserve merge conflicts when they do arise. It's very simple!
