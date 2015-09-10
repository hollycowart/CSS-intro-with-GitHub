# Git Branches

Now you're going to do something rather sophisticated in your GitHub app.

You're going to create a new **branch.** This will enable you to make changes and even create new files without affecting any of the original files in your repo.

More important, by working only in a branch, later you will be able to make a **pull request** to the original repo. *This can only be done from a branch.* If the owner of the original repo allows it, your branch can then be **merged** into that original, incorporating your changes and new files into it. This is how thousands of people collaborate and contribute to [open-source](http://opensource.com/resources/what-open-source) projects.

Before you create a branch, make sure you have done everything [here](../github_basics) and [here](../../../README.md). Don't skip anything.

## See branches in the GitHub app

First find the Branch button near the top left of the app window. This is the **branch icon**:

![GitHub branch icon](../images/git-branch.png)

To the left of the Branch button is a button bearing the name of the current branch. Right now, that is *master.* The first branch of a repo is always named *master* by default.

When you click the button that says *master,* you'll see a list of all the branches in this repo. Even now, *master* has a checkmark to show you it is the current branch -- the one you are in now.

Branches are like parallel universes. What happens in one branch has no effect on any other branches.

The “parallel universes” analogy is really appropriate, because when you are in branch A, *you cannot see any of the files in branch B,* even though they are all local files on your hard drive. There is no chance of polluting any other branch.

## Create a new branch

In your GitHub app, click the button with the **branch icon.** You will see a field into which you can type the name of a new branch.

Type the word *assignment* and a hyphen and your own last name. For example:

**assignment-mcadams*

Click the “Create Branch” button.

You should see your new second branch immediately.

## What is the branch?

Your new branch is a perfect copy of all the files in *master.* Everything in *master* now exists as a copy in your *assignment* branch.

## Switching between branches

This can be tricky, so pay attention. Remember the idea of "parallel universes"? Keep that in mind, because branches are NOT like folders. You can't simply move stuff back and forth between them. But *you* can move between branches.

Mac: In your app, still in the Branches window, double-click the new branch. There should be a clear indicator (a checkmark) to tell you which branch you are in now. You'll see the name of the current branch at the top left of the app window.

Windows: In your app, the name of the current branch appears at the top right of the app window. If you're not in *assignment* now, open the branch list and click to switch.

## Your assignment

For this assignment, I want you to do EVERYTHING in your *assignment* branch. Do not make any edits or other changes while you are in *master.* So **switch to your *assignment* branch,** and then **stay in it.**

This will allow you to do the pull request successfully, later.

## Next steps

To continue with your assignment, go back to the top of this repo, where all files and folders are listed. Go into the folder named *assignment* and follow the instructions there.

Remember to stay in your *assignment* branch! Do not switch branches again.
