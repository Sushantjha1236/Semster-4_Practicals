# Editing a file and committing changes on GitHub
## About Commits
Similar to saving a file that's been edited, a commit record changes to one or more files in your branch. Git assigns each commit a unique ID, called a SHA or hash, that identifies:
- The specific changes
- When the changes were made
- Who created the changes<br>

When committing, you must include a commit message that briefly describes the changes. You can also add a co-author on any commits you collaborate on.
If the commits you make in GitHub Desktop are associated with the wrong account on GitHub, update the email address in your Git configuration using GitHub Desktop.
Repository administrators can enable rulesets for a branch to enforce specific conventions when committing. For example, a ruleset can require a commit to be signed or an issue number to be referenced at the start of a commit message. GitHub Desktop will display a warning and prevent committing if a commit does not follow the rulesets.
## Steps to make a commit on Git
- Clone the repository: git clone <repository_URL>
- Navigate to the repository: cd <repository_name>
- Make changes to files.
- Check the status: git status
- Stage the changes: ' git add <file_name> ' or 'git add .'
- Commit the changes: git commit -m " Your commit message here "
Push changes to the remote repository: git push origin <branch_name><br>
![Screenshot 2024-03-03 164919](https://github.com/Sushantjha1236/Semster-4_Practicals/assets/113833084/569f46b4-3bd6-434c-a411-0f8d3c1082d6)
## Navigate to the GIT-Hub [Experiment-2.1 file](https://github.com/Sushantjha1236/Semster-4_Practicals/blob/main/Git%20and%20Git-Hub/Git%26Git_Hub-Exp-4/Git_Experiment2.1.pdf)
