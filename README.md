# To know status
git status
# commit
git commit -m "message"
# Adding to remote repo
git remote add origin https://github.com/yourusername/my_python_project.git 

# Now code is in master branch, Push Code to GitHub
git push origin master  # Push the changes to GitHub 

# Rename branch name
git push -u origin cal-sum,sub.py

# Push Code to GitHub
git push -u origin cal-sum,sub.py 

 # Create a branch
git branch feature-multiplication 

# Switch to the branch
git checkout feature-multiplication  

+++

git add multiplication.py

git commit -m "multiplication"

git merge feature-multiplication

git status

+++

# Push Code to GitHub
git push origin master

-----------------------------------------------------------
# Undo a Change (If Needed)
# If You Want to Revert Last Commit but Keep Changes:

git reset --soft HEAD~1

# If You Want to Remove Changes Completely:
git reset --hard HEAD~1
-----------------------------------------------------------
# Delete a Branch After Merging
git branch -d feature-multiplication

# If the branch is not merged, force delete:
git branch -D feature-multiplication
------------------------------------------------------------
# If You Want to Save Changes Without Committing:

git stash
# Restore Stashed Changes:

git stash pop
