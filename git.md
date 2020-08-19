# Git cheatsheet

To push code to new repo for the first time: <br>
	`create repo in github`
	Go to folder containing project in local <br>
	`cd ~/Desktop/DS-and-ML-bootcamp`
	Initiate git <br>
	`git init
	# >Initialized empty Git repository`
	Add all files <br>
	`git add -A`
		NOTE: .gitignore might also be needed <br>
	Cofigure user.name and user.email if not already set <br>
	`git config --global user.email "you@example.com"
	git config --global user.name "Your Name"`
		NOTE: Omit --global to set the identity only in this repository.<br>
	Add remote repo <br>
	`git remote add origin https://github.com/shivamagrawal3900/DS-and-ML-bootcamp.git`
	Push the repo <br>
	`git push -u origin master`
	<br>	
	Done!!


To Change user, this can be used when access denied error is there <br>
`git config credential.username "new_username"`


