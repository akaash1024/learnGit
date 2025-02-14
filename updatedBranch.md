git branch


Run this to check remote branches:
git branch -r


To see both local and remote branches:
git branch -a


2️⃣ Push Local Branches to Remote
git push origin branch-name
Do this for each missing branch.


If you suspect the remote has branches that aren’t showing locally, update your local repo:
git fetch --all

Then check again:

git branch -a



4️⃣ Delete Local Branches (If Needed)
git branch -d branch-name


For force deletion (if the branch is not merged):
git branch -D branch-name


If a branch is missing on GitHub but still showing locally, it might have been deleted remotely. To remove references to deleted remote branches:
git remote prune origin


Final check
git branch -a




