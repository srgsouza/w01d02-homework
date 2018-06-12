- What command do you use to setup a git repository inside of your folder?
git init
- What command do you use to ask git to start tracking a file?
git add <file(s)>
- What command do you use to ask git to move your file from the staging area to the repository?
git commit -m 'message'

- What command do you use to pull any changes from the master repository into your local repository?
git pull origin master (when on the master repo)
- What command do you use to unstage a file?
git reset HEAD -- path/to/file
- What command do you use to change your files back to how they were after a commit?
git checkout -- <file>
- Why is it important to use -- when changing files back to a previous state?
- Why might you want to reset your files back to a previous commit?
When you realize you don't want the changes / commit you've made

- What command do you use to create a branch?
git checkout -b branchName
- What command do you use to use a different branch?
git checkout branchName
- Why would you want to use a branch other than the default master?
To track code separately from the main branch. 

- Give an example for when you would use git merge and give an example for when it would be better to submit a pull request to have your branch merged
"used by git pull to incorporate changes from another repository ". A pull request goest to an assignee for review/approval
- What command do you use to send all of the work that you've done locally to your remote repository?
git push

