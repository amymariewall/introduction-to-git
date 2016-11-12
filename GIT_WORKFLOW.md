# New Feature Template

Every time you begin working on a new feature, follow this template.

## Preliminary Steps

First, identify which task you will be working on (which question you will be answering).

Next, make sure your Git repo is actually in the right state to begin a new feature:

(If this is the _very first_ feature for this project, and you haven't done any work yet, then you should skip to the 'Create Branch & Pull Request' section.)


## Create Branch & Pull Request

If you have a task defined and are ready to begin, cut a new branch for the feature using the GitHub Desktop App.

## Build Feature

Work through this one feature--stay focused on just this task.

Work through answering the question using Markdown and Sublime Text.

Then, commit your changes that you made for that feature. The commit message must include a brief title of the feature and the Issue number associated with that feature:

"Favorite entertainer. Issue #12"`

Sync the changes with GitHub. Create a pull request in your repository for that feature.


## Merging

When you are 100% complete with a task, here are the steps for merging it into 'master':

1. Make sure everything for the task is completed and committed, and a Pull Request has been created.
2. Switch to the 'master' branch. `git checkout master`... Then: sync to be sure there are no changes that you may have missed from other collaborators.
3. Navigate to the Pull Request that has been created in your repository.
4. If everything looks good, merge your feature branch into master using the GitHub interface.
5. Now check the PR for this issue. It should indicate that its code has been merged. It probably auto-closed the issue. If not, you can 'close' the PR. Either way, you may choose to delete the branch from GitHub after the PR is closed.
6. Update your list of tasks in GitHub Issues.
