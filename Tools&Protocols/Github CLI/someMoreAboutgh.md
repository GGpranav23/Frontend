# GitHub CLI (gh) Cheat Sheet

## 1. Clone a repository

Clone a GitHub repository to your local machine:

```bash
gh repo clone <username>/<repoName>
```

* Replace `<username>` with the repository owner.
* Replace `<repoName>` with the repository name.
* Clones the repo into a folder named `<reoName>` in your current directory.

## 2. Useful GitHub CLI Commands

| Command                      | Description                                                    |
| ---------------------------- | -------------------------------------------------------------- |
| `gh auth login`              | Log in to your GitHub account via CLI.                         |
| `gh auth status`             | Check if you are logged in and which account is active.        |
| `gh repo list`               | List all repositories for your account or a specific user/org. |
| `gh repo view <repo>`        | View detailed information about a repository.                  |
| `gh issue list`              | List issues in the current repository.                         |
| `gh pr list`                 | List pull requests in the current repository.                  |
| `gh pr create`               | Create a new pull request from the CLI.                        |
| `gh pr checkout <pr_number>` | Check out a pull request locally.                              |
| `gh gist create <file>`      | Create a GitHub Gist from a file.                              |
| `gh api <endpoint>`          | Make a direct GitHub API call.                                 
