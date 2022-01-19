# Locally created repo
Repo created in VS Code using Terminal.

## Steps
1. Create a folder for the repo (e.g."fcc-demo-repo-local")
2. Make sure you're in the right directory in the Terminal panel (can navigate there manually, or by using commands like "cd ../")
3. Create a file like README.md and add some text like I've done here.
4. Initialize repository with "git init"
5. git status
6. git add README.md
7. git status
8. git commit -m "Created README" -m "vague description"
9. Create new (empty) repo on GitHub
10. git remote add origin git@github.com:cw1984/fcc-demo-repo-local.git
11. git remote -v
12. (EITHER “git push origin main” OR “git push -u origin main” (“-u” stands for “upstream” and means that we’re setting the default upstream branch, so we can just type “git push” each time))
13. “git push” gave me the following message: “fatal: The current branch master has no upstream branch. To push the current branch and set the remote as upstream, use git push --set-upstream origin master”
14. git push --set-upstream origin master
