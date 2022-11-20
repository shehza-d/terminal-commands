# Terminal-Commands
## All basic terminal commands in one place
<h3 align="center">Show some ❤ by <img src="https://imgur.com/o7ncZFp.jpg" height=25px width=25px> some repositories</h3>

You can contribute to this readme
If you to contribute with a loooot of commands make a new .txt file / if you see old commands don't tell me fork it and feel free to contribute in this OpenSource Project..

<hr>
<p text-align="center">

[Git Commands](https://github.com/shehza-d/Terminal-Commands#git-commands)

[React Commands](https://github.com/shehza-d/Terminal-Commands#react-commands)

[Node Commands](https://github.com/shehza-d/Terminal-Commands#node-commands)

[ExpressJS Commands](https://github.com/shehza-d/Terminal-Commands#expressjs-commands)

[FireBase Commands](https://github.com/shehza-d/Terminal-Commands#firebase-commands)

[Netlify Commands](https://github.com/shehza-d/Terminal-Commands#netlify-commands)

[TypeScript Commands](https://github.com/shehza-d/Terminal-Commands#typescript-commands)

[Important NPM Packages](https://github.com/shehza-d/Terminal-Commands#important-npm-packages)

[Linux COMMANDS](https://github.com/shehza-d/Terminal-Commands#linux-commands)
</p>
<hr>

## Git Commands

```
Initailizing a respoitory
git init

Staging Files

git add file1.js             | stage a single file
git add file1.js file2.js	 | stage multiple files
git add *.js				 | stage with a pattern
git add.					 | stage current directory






VIEWING STATUS
git status			|Full Status
git status -s		|Short status



Committing the staged files
git commit -m “Message” | Commits with a one-line message
git commit | Opens the default editor to type a long message 



Skipping the staging area
git commit -am “Message” 



git rm file1.js 	| Removes from working directory and staging area
git rm --cached file1.js | Removes from staging area only



Renaming or moving files
git mv file1.js file1.txt



Viewing the staged/unstaged changes
git diff 	| Shows unstaged changes
git diff --staged | Shows staged changes
git diff --cached | Same as the above 




Viewing the history
git log 	| Full history
git log --oneline 	| Summary
git log --reverse 	| Lists the commits from the oldest to the newest






Viewing a commit
git show 921a2ff 	| Shows the given commit
git show HEAD 		| Shows the last commit
git show HEAD~2 	| Two steps before the last commit
git show HEAD:file.js | Shows the version of file.js stored in the last commit 




Unstaging files (undoing git add)
git restore --staged file.js # Copies the last version of file.j


Discarding local changes
git restore file.js 				 |Copies file.js from index to working directory
git restore file1.js file2.js 		 |Restores multiple files in working directory
git restore . 						 |Discards all local changes (except untracked files)
git clean -fd 						 | Removes all untracked files 



Viewing the history
git log --stat 						 |Shows the list of modified files
git log --patch 					 |Shows the actual changes (patches) 


Restoring an earlier version of a file
git restore --source=HEAD~2 file.js



Finding contributors
git shortlog


Branching & Merging
Managing branches
git branch bugfix 					# Creates a new branch called bugfix
git checkout bugfix 				# Switches to the bugfix branch
git switch bugfix 					# Same as the above
git switch -C bugfix 				# Creates and switches
git branch -d bugfix 				# Deletes the bugfix branch
Comparing branches
git log master..bugfix 				# Lists the commits in the bugfix branch not in master
git diff master..bugfix 			# Shows the summary of changes
Stashing
git stash push -m “New tax rules” 	# Creates a new stash
git stash list 						# Lists all the stashes
git stash show stash@{1}			 # Shows the given stash
git stash show 1 					# shortcut for stash@{1}
git stash apply 1					 # Applies the given stash to the working dir
git stash drop 1					 # Deletes the given stash
git stash clear 					# Deletes all the stashes
Merging
git merge bugfix 					# Merges the bugfix branch into the current branch
git merge --no-ff bugfix 			# Creates a merge commit even if FF is possible
git merge --squash bugfix			 # Performs a squash merge
git merge --abort 					# Aborts the merge



Viewing the merged branches
git branch --merged 				# Shows the merged branches
git branch --no-merged				 # Shows the unmerged branches
Rebasing
git rebase master 					# Changes the base of the current branch
Cherry picking
git cherry-pick dad47ed 			# Applies the given commit on the current branch
Collaboration
Cloning a repository
git clone url
Syncing with remotes
git fetch origin master				 # Fetches master from origin
git fetch origin 					# Fetches all objects from origin
git fetch 								# Shortcut for “git fetch origin”
git pull							 # Fetch + merge
git push origin master				 # Pushes master to origin
git push							 # Shortcut for “git push origin master”
Sharing tags
git push origin v1.0				 # Pushes tag v1.0 to origin
git push origin —delete v1.0
Sharing branches
git branch -r 						# Shows remote tracking branches
git branch -vv 						# Shows local & remote tracking branches
git push -u origin bugfix			 # Pushes bugfix to origin
git push -d origin bugfix 			# Removes bugfix from origin
Managing remotes


git remote 						# Shows remote repos
git remote add upstream url 		# Adds a new remote called upstream
git remote rm upstream 			# Remotes upstream 


```

```
git --version
```
```
git add *

git commit -m "Pushing new Changes"

git push origin main 
```

first time

	git config --global user.name "Shehzad”
	git config --global user.email "shehzaddiqbal@gmail.com”
```
git status
```

<hr>

## React Commands
~~~
npx create-react-app myappname
~~~
(to create react project)
~~~
npm start
~~~
(to start app)

	npm run build
(this build a final folder run this after project is finished)

```
npm i react-router-dom
```
```
npm install react-icons --save
```
<hr>

## Node Commands
```
node --version
```
```
node fileKaName
```

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
```
```
npm i prompt-sync
```
installing nvm
```
nvm install (version) like (12.16.3)
phir
```
```
nvm use 12.16.3
```

## ExpressJS Commands
```
npm init -Y
```
(to initinil node project is easy words to create package.json)  -y for default settings

	npm install express

(to initilize express project express ky liye)
```
npm i cors
```

<br>

## FireBase Commands
```
npm install -g firebase-tools
```
(install CLI(also use this command to update CLI))

	firebase login

(first time only)

	firebase init

(initilize project(apne project ma run karna ye))

	firebase deploy --only hosting

firebase deploy other options  [(--only hosting),(--only database),(--only storage),(--only firestore),(--only functions)]


```
npm install firebase@9.12.1 --save
```
fireStore
```
firebase --help
```
```
firebase logout
```
## Netlify Commands
```
npm install netlify-cli -g 
```
(first time only)
```
netlify login
```
(first time only)
!(netlify init)
```
netlify deploy --prod
```

    netlify status
```
netlify help
```
```
netlify logout
```
<!-- ## MongoDB Commands
```
npm i mongoose
``` -->

## Material UI
```
npm install @mui/material @emotion/react @emotion/styled
```
```
npm install @mui/material @mui/styled-engine-sc styled-components
```
```
npm install @fontsource/roboto
```
```
npm install @fontsource/roboto
```
## TypeScript Commands 
```
npm install typescript --save-dev
```
```
npm i -g typescript
```

```
tsc --init
```
(to make ts.config)
```
tsc (file ka nam)eg. tsc index.ts
```
```
npx create-react-app app_name --template typescript 
```

## ( React + Redux + TypeScript ) Command
```
npx create-react-app app_name --template redux-typescript 
```
## Important NPM Packages
```
npm i mongoose
```
<!-- Formik i Commands -->
```
npm install formik --save
```
<!-- ## yup i Commands -->
```
npm i yup
```
<hr>

## Linux COMMANDS 

1. cd
dir or ls (to view files in directories)



## DotNet on Ubuntu for C#

sudo apt-get install wget apt-transport-https

wget https://packages.microsoft.com/config/ubuntu/20.04/packages-microsoft-prod.deb

sudo dpkg -i packages-microsoft-prod.deb 

sudo apt-get update

sudo apt-get install dotnet-sdk-5.0 

dotnet --version



