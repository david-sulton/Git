# Getting Started
- create personal access token (settings>developer settings>personal access tokens>create new token
- Download git https://git-scm.com/downloads

## Git
    mkdir github
    dir
    cd github
    mkdir myproject
    git init
    git config --global user.name "username"
    git config --global user.email "email"
    git remote add <local repo name> <repo_URL_from_github>
    git remote -v
    git remote set-url <local repo name> https://<username>:<Token>@github.com/<username>/<Repository>.git
    git fetch <local repo name>
    git log
    git switch main
    git branch
    git pull <local repo name>
    git log
    q
    dir
    notepad.exe <file_to_change> #change and save
    git add .
    git commit -m "message to relay for commit"
    git push <local rep name>
    
    
### Notes
- clone- downloads a copy of a repository
- add- Add a file to a commit
- commit- stage changes with a message
- push- Copy a commit to the repository
- pull- pull down commits from repository
