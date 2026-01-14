**Git help**

I use this page to update all my learnings of git

1. **clone a repo:**
    `git clone https://github.com/your-username/your-repo-name.git`

2. **check the status of the changes made:**
    `git status`

3. **Stage your changes:**
    `git add <file>`

4. **commiting the changes:**
    `git commit -m "commit-msg"`

5. **finding the remote repo:**
    `git remote -v`

6. **pushing the changes:**
    `git push <remote repo> <branch>`
    `git push origin main`

7. **reset the branch to a commit (commits that hasn't been pushed)**
    `git reset --hard <remote repo>/<branch>`
    `git reset --hard HEAD~n #n = number of commits to remove`

8. **switch to a branch:**
    `git checkout <branch name>`

9. **make a new branch:**
    `git checkout -b <new branch name>`

10. **merging the new branch to the main**
    `git merge <new branch name>`
    **pushing the merge changes to the main**
    `git push origin main`

11. **pulling the changes from repo to stay upto date**
    `git pull origin main
