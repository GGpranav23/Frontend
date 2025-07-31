Prerequisite: Scoop
How to install: **1. run pwsh as admin**
                **2. Set-ExecutionPolicy RemoteSigned -Scope CurrentUser**
                **3. iwr -useb get.scoop.sh | iex** (Run this without admin) 

1. Authenticate with GitHub
    gh auth login

2. Go to your project folder (or create one)
   Initialize git by running "git init"

3. Stage all files: "git add ."

4. Commit: git commit -m "Initial commit"

5. Before creating repo check the branch name using "git branch". 

6. If you prefer "main" and current is master then rename the master to main using "git branch -M main".

7. gh repo create reponame --public --source=. --remote=origin --push



### Post Setup

1. Check status (see what changed): git status

2. Stage your changes: "git add ". OR use "git add filename.ext" to add specific files.

3. Commit your changes: "git commit -m "Your message here"

4. git push

5. If this is your first push on a branch, or the branch is new: "git push -u origin main"

6. See your commit history: git log --oneline

                                    



