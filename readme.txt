how to use git/github

1. create github account
2. create repository
3. clone the repository to your hard drive:
	git clone https://github.com/cocobaco/learn-git.git
4. go to your local directory:
	cd learn-git
5. make local edits, make new files, inside that directory
6. add files (-A here means all files in the dir):
	git test1.py
	git add -A
7. see status (optional):
	git status
8. commit with a message:
	git commit -m 'write about what you have done'
9. push the files to github (may use other branch name):
	git push origin master
10. get files from github
	git pull origin master
11. create a new branch
	git branch new_branch
12. switch branch
	git checkout new_branch
13. see changes
	git log
14. see differences between commits
	git diff <commit-id1> <commit-id2>
	git diff HEAD^ HEAD
