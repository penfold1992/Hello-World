# [Hello World!](https://github.com/penfold1992/Hello-World)

## Contents
 - [Git Commands](#git-commands)
  - [Creating a Repo](#creating-a-repo)
   - [Creation](#creation)
   - [Commit your files](#commit-your-files)
   - [Push the commit](#push-the-commit)
  - [Fork a Repo](#fork-a-repo)
   - [Clone a Repo](#clone-a-repo)
   - [Configure Remote](#configure-remote)
  - [Additional Tools](#additional-tools)
 - [Readme tips](#readme-tips)
  - [Task Lists](#task-lists)
  - [Emoji's](#emojis)
  - [Syntax Highlighting](#syntax-highlighting)
   - [Visual Basic](#visual-basic)

## Git Commands
For use on git bash.

### Creating a Repo

#### Creation

```
$ mkdir ~/Hello-World
# Creates a directory for your project called "Hello-World" in your user directory
$ cd ~/Hello-World
# Changes the current working directory to your newly created directory

$ git init
# Sets up the necessary Git files
# Initialized empty Git repository in /Users/you/Hello-World/.git/

$ touch README
# Creates a file called "README" in your Hello-World directory
```

#### Commit your files

```
$ git add README
# Stages your README file, adding it to the list of files to be committed
$ git commit -m 'first commit'
# Commits your files, adding the message "first commit"
```

#### Push the Commit

```
$ git remote add origin https://github.com/username/Hello-World.git
# Creates a remote named "origin" pointing at your GitHub repository
$ git push origin master
# Sends your commits in the "master" branch to GitHub
```

### Fork a Repo

#### Clone a Repo

```
$ git clone https://github.com/username/Spoon-Knife.git
# Clones your fork of the repository into the current directory in terminal
```

#### Congifure Remote

```
$ cd Spoon-Knife
# Changes the active directory in the prompt to the newly cloned "Spoon-Knife" directory
$ git remote add upstream https://github.com/octocat/Spoon-Knife.git
# Assigns the original repository to a remote called "upstream"
$ git fetch upstream
# Pulls in changes not present in your local repository, without modifying your files
```

### Additional tools

Pushing a commit back to your remote repository on github

```
$ git push origin master
# Pushes commits to your remote repository stored on GitHub
```

Pull in upstream changes

```
$ git fetch upstream
# Fetches any new changes from the original repository
$ git merge upstream/master
# Merges any changes fetched into your working files
```

More information can be found at these links:

| Links |
| ----- |
| [Create a repo](https://help.github.com/articles/create-a-repo) |
| [Fork a repo](https://help.github.com/articles/fork-a-repo) |
| [Github Guides](https://guides.github.com) |
| [Youtube Github Guides](https://www.youtube.com/user/GitHubGuides) |

## Readme tips

### Task Lists
Task lists can be created by entering
```
 - [x] Task 1
 - [ ] Task 2
 - [ ] Task 3
```
 - [x] Task 1
 - [ ] Task 2
 - [ ] Task 3
 
### Emoji's
1. :uk: - `:uk:`
2. :x: - `:x:`
3. :weary: - `:weary:`
4. :warning: - `:warning:`
5. :unlock: - `:unlock:`
6. :-1: - `:-1:`
7. :+1: - `:+1:`
8. :clap: - `:clap:`
 
 [More can be found here:](https://github.com/scotch-io/All-Github-Emoji-Icons)
 
### Syntax Highlighting
 [More can be found here:](http://tinker.kotaweaver.com/blog/?p=152)
 
###Visual Basic

	```vb.net
	Dim num1 As Integer
	Dim num2 As Integer
	'Testing VB Commenting
	
	num1 = 5
	num2 = 10
	debug.print num1 + num2
	```

Will produce:
	
```vb.net
Dim num1 As Integer
Dim num2 As Integer
'Testing VB Commenting

num1 = 5
num2 = 10

debug.print num1 + num2
```