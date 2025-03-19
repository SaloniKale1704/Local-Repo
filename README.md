# This is Readme File

Git (Version Control System) - distributed version control system designed to handle everything from small to very large projects with speed and efficiency.
GitHub -It provides a collaborative environment for developers to work on projects together.(allows developers to store and manage their code using Git)
	=> Folders(repositories)

permanent changes - add(staged) -> commit
We can use html code in README to move cursor to next line  <br>

Setting up Git - 
1. Visual Studio Code
2. Window(Git Bash)

git --version : To check the version of git
git config --global user.name "Demo2"
git config --global user.email "salonikale137@gmail.com"
git config --list
git clone <url>: cloning a repo on our url - eg. git clone https://github.com/SaloniKale1704/Demo2.git
cd <folder_name> : change directory
cd .. : to move backward in path
ls : list of files inside folder
git status: give status of code
	1. Untracked file - new file that doesn't exist track
	2. Modified - changed
	3. Staged - file is ready to commit
	4. unmodified - file is ready to be committed
git add <file_name> : adds new or changed files in working directory to staging area
git add . : to add all changes
git commit -m "meaningful message" : to commit code with message
git push origin main : upload local repo content to remote repo

M - Modified File
U - Untracked File

Init commands - to create a new repo (staring any project from scratch in VS code)
git init : to initialize new repo
git remote add origin <link>: we are adding new remote(new repo)
git remote -v : to verify remote
git branch : to check branch (main - default branch)
git branch -M main : to rename branch name to main
git push -u origin main : (u) to set upstream

Workflow
Github repo -> clone -> changes -> add -> commit (with msg) -> push

Git Branches 
git branch : to check all branches  
git branch -m new_name : To rename branch
git checkout <branch_name> : to navigate another branch(from current)
git checkout -b <branch_name> : to create new branch
git branch -d <branch_name> : to delete branch

Merging code
way 1 - 
	git diff <branch_name> : to compare commits, branches, files and more
	git merge <branch_name> : to merge 2 branches

Way 2 -
create a PR (pull request) : tell others about changes you've pushed to branch in repo on Github

Pull Command 
git pull origin main : used to fetch and download from remote repo and immediately update local repo

Merge Conflicts
When git is unable to automatically resolve differences in code between two commits

Undoing changes
1. staged changes (added, not committed)
	git reset <file_name>
	git reset : reset all files
2. Committed changes (for one commit)
	git reset HEAD~1
3. Committed changes (many commits)
	git reset < commit hash>
	git reset --hard <commit has>
git log : to check all commits


Fork (rough copy)
a new repo that shares code and visibility setting with original "upstream" repo

git stash : save your uncommitted changes without committing them into repo. 



 

