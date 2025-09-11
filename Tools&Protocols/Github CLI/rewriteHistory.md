Important Run this command to update the author info for the last commit only:
## git commit --amend --author="Your Correct Name <your_email@example.com>"

Important To rewrite all commits in the branch:
## git filter-branch --env-filter '
## if [ "$GIT_COMMITTER_EMAIL" = "wrong_email@example.com" ]
## then
##     GIT_COMMITTER_NAME="Your Correct Name"
##     GIT_COMMITTER_EMAIL="your_email@example.com"
##     GIT_AUTHOR_NAME="Your Correct Name"
##     GIT_AUTHOR_EMAIL="your_email@example.com"
## fi
## ' --tag-name-filter cat -- --branches --tags
