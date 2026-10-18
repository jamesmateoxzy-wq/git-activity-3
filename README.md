# git-activity-3

Repository: jamesmateoxzy-wq/git-activity-3

1. Clone and check the repository
git
clone https://github.com/jamesmateoxzy-wq/git-activity-3.git

Purpose:
Downloads the repository to the computer.

2. Create and commit the initial file
git
status

Purpose:
Checks the current branch and working-tree status.

git
add
git-activity.txt

Purpose:
Stages the activity file for a commit.

git
commit -m "Initial commit"

Purpose:
Records the initial file in Git history.

git
push
origin main

Purpose:
Pushes the local main branch to GitHub.

3. Create and push a feature branch
git
switch -c feature-branch

Purpose:
Creates and switches to feature-branch.

git
add
git-activity.txt

Purpose:
Stages the change made on the feature branch.

git
commit -m "Update file
in feature branch"

Purpose:
Records the feature-branch change.

git
push
-u origin feature-branch

Purpose:
Pushes the branch to GitHub and sets its upstream.

4. Merge the feature branch into main
git
switch main

Purpose:
Switches back to the main branch.

git
merge feature-branch

Purpose:
Merges the feature-branch changes into main.

git
push
origin main

Purpose:
Pushes the updated main branch to GitHub.

5. Pull the change made directly on GitHub
git
pull
origin main

Purpose:
Fetches and integrates the latest main branch from GitHub. In this session, Git reported that the branch was already

up to date.

6. Verify the final file and status
cat
git-activity.txt
Page 2

Purpose:
Displays the file contents in Git Bash.

git
status

Purpose:
Confirms whether there are uncommitted changes and whether the branch is synchronized.

Final verification:
The local main branch was up to date with origin/main, the working tree was clean, and git-activity.txt

contained the initial text, the feature-branch change, and the change made directly on GitHub
