# Git-basics
This repo contains the git basics taught by Shradha dii of Apna college (you can go throught this and save your time). 



# From repo to local
git clone https://...

# Add all changes to the staging area
git add .

# Commit the changes with a message
git commit -m "msg"

# Push the changes to the remote repository (main branch)
git push origin main

# From local to repo
git add .

# Commit the changes with a message
git commit -m "msg"

# Add a remote repository (newRepoLink)
git remote add origin https(newRepoLink)........

# To verify remote repositories
git remote -v

# To check the current branch
git branch

# To rename the branch
git branch -M nameOrMain

# To push to the online repo
git push origin main
# or
git push -u origin main
# With this, you have set the upstream (-u) and can use "git push" from the next time

# Branches
git checkout -b <new_branch_name>

# To switch to an existing branch
git checkout <branch_name_u_want_to_navigate>

# To delete a branch
git branch -d <branch_to_be_deleted>

# To compare changes between branches
git diff <branch_name_to_be_compared>

# To merge a branch or create a pull request
git merge <branch_to_be_merged_with>

# To fetch from the cloud to the local machine
git pull origin main

# Display the commit history and see hash code
git log

# Undoing changes

# 1. When you add but don't commit
git reset <file_name>
# or
git reset
# (for all changes)

# 2. If you add and do commit both and want to go 1 step back
git reset HEAD~1

# 3. If you add and do commit both and want to go x step back
git reset <hash_code_of_x_steps_before>
# or
git reset --hard <hash_codehash_code_of_x_steps_before>
# (to reverse changes from the editor also)

# Fork (creating a rough copy of any project to work with)
