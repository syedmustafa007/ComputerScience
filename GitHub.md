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
- .git Directory: The .git folder contains all the information that is necessary for your project in version control and all the information about commits, remote repository address, etc. All of them are present in this folder. It also contains a log that stores your commit history so that you can roll back to history.

## GitHub commands
- `git init`: This command is used to convert a linux folder into a local git repository. When you run this command .git file is created.
- `git add <file_name>`: Stage files into local Git repository. Example `git add Sofrware.md`
- `git status`: Check status of added files
- `git commit -m "message"`: Commit added files with a message
- `git log`: See all commits
- `git reset HEAD~1`: Deletes recent commit
- `git push -u <REPO_LINK> main`: Push a commit to Github.
- `git pull <REPO_LINK> main`: Pull all commits from Github to linux. 
- `git diff` : Shows the differences and changes you have made in your project.
## **Github Examples**
```
root@Dragonator:~/mustafa/Computer Science# git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   GitHub.md

no changes added to commit (use "git add" and/or "git commit -a")
root@Dragonator:~/mustafa/Computer Science# pwd
/root/mustafa/Computer Science
root@Dragonator:~/mustafa/Computer Science# git add GitHub.md
root@Dragonator:~/mustafa/Computer Science# git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   GitHub.md

root@Dragonator:~/mustafa/Computer Science# git commit -m "Feat: pushing github examples"
[main 327b14b] Feat: pushing github examples
 1 file changed, 2 insertions(+)
root@Dragonator:~/mustafa/Computer Science# git log
commit 327b14bac8abba7f1a046d76c569ce6032465245 (HEAD -> main)
Author: Syed Mustafa <syed.mustafa7418@gmail.com>
Date:   Sun Jun 29 06:56:22 2025 +0300

    Feat: pushing github examples

commit ebec634f8b30ebccb6dd173e87655a1fe7968139
Author: Syed Mustafa <syed.mustafa7418@gmail.com>
Date:   Sun Jun 29 06:40:23 2025 +0300

    Feat: pushing github and software notes

commit 10a42c4297dde2e259136929c2a9f439174c120b
Author: Syed Mustafa <syed.mustafa7418@gmail.com>
Date:   Sun Jun 29 04:40:11 2025 +0300

    feat: pushing hardware and software notes to github

commit ae6c1b0ac31ec85b41eb63ea3fc3108cd895f3f3
Author: syedmustafa007 <syed.mustafa7418@gmail.com>
Date:   Sun Jun 29 03:28:00 2025 +0300

    Initial commit
root@Dragonator:~/mustafa/Computer Science# git push -u https://github.com/syedmustafa007/ComputerScience.git main
Username for 'https://github.com': syedmustafa007
Password for 'https://syedmustafa007@github.com':
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 406 bytes | 406.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/syedmustafa007/ComputerScience.git
   ebec634..327b14b  main -> main
branch 'main' set up to track 'https://github.com/syedmustafa007/ComputerScience.git/main'.

root@Dragonator:~/mustafa/Computer Science#
```