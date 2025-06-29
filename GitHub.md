# GitHub
GitHub is a version control tool that is used to collaborate with teams, share code and perform version control.

## Git concepts
- User: A user has a GitHub account and username. Example: `syedmustafa007`.
- Repository: A repository is used for a user to store their projects on Github. Example: `Computer Science`
- Branch: A branch on a github repository is used to organize code from team members. Example: `main`
- Stage: A stage is used to add changes from local directory for commit. Example: `git add Software.md`
- Commits: A commit is used to finalize changes that will be sent to GitHub. A commit also has a message.
- Push: A push is an operation that sends a commit to Github.
- Pull: A pull is an operation that pulls commits from Github to linux. 

## GitHub commands
- `git init`: This command is used to convert a linux folder into a local git repository.
- `git add <file_name>`: Stage files into local Git repository. Example `git add Sofrware.md`
- `git status`: Check status of added files
- `git commit -m "message"`: Commit added files with a message
- `git log`: See all commits
- `git reset HEAD~1`: Deletes recent commit
- `git push -u <REPO_LINK> main`: Push a commit to Github.
- `git pull <REPO_LINK> main`: Pull all commits from Github to linux. 
