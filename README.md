# git-command
test repo for git command demonstration.
git clone "paste copied url"
git init
git status "shows changes in dir"
git add - name
git commit -m ' '
git push
git difftool HEAD 'shows diff between previous code and new code "


open source
version control steps
after fork
clone  
		git clone https://github.com/your-username/repository.git
branch  
		cd repository
		git branch new-branch
checkout 
		git checkout new-branch
combination
		git checkout -b new-branch
go to master back 
		git checkout master
If changes made or added new file
		git add -A  (-A means all),to perform changes
** commit ** 
		git commit -m "Fixed documentation typos"
		git commit (If minor change)
text editor in git commit
		git config --global core.editor "nano"   or "vim"
( around 50 characters long. Under this, and broken up into digestible sections)
verify commit
		git status
push the changes
		git push --set-upstream origin new-branch
check local repository is up to date with upstream repository
	(Remote repositories)
		git remote -v
specify a new remote upstream repository for us to sync with the fork.
		git remote add upstream https://github.com/original-owner-username/original-repository.git
Sync the Fork
		git fetch upstream
	(commits to the master branch will be stored in a local branch called upstream/master.)
switch to the local master branch of our repository		
		git checkout master
merge changes to local master branch
		git merge upstream/master
*****Create Pull Request*****
		
