`git init` - power your folder to be managed by git and created a new empty repository . it also create a .git folder that holds all relavant logic to manage versions of your project.

`Working area` - There can be a bunch of files that are not currently handled by git; it means that changes done or to be done are not managed by git .A file which is in the working area is not considered to be in the staging area.When we do git status and we see a bunch of untracked files then these are actually called to be in the working area.

`Staging area` - what all files are going to be part of the next version that we will create. This staging area is the place from which git knows what changes will be done from last version to next version.

`Repository area` : This area actually contains the details of all your previous registered versions.whenever we registered a version all of that data is stored in this area. All the files in this area git already manage them and know their version history.

`git add <file>` : this moves file from working area to staging area.

`git rm --cached <file>` : moves file back from staging area to working area.

`commit` : commit is a particular version of the project . It captures the Snapshot of the project staged changes and creates a version out of it.

`git commit` : registers staging changes to a commit.

`git log` : lists down all the commits of the repository.If you want to exit out of git prompt press `q`.

`git restore <filename>` : it remove all files changes from the staging Area to be committed. This can be useful , if we did some dirty pieceOf code and now no more want it instead of deleting every change Line by line we can restore or we can say restore last version of the file.

`Difference between git rm and git restore`: when we want to move Whole file back to untracked area we do git rm otherwise if we just Want to changes to be moved to working or staging area then we do git restore.

git diff commit1 commit2 : it gives the Difference of all files changes between two commit.

git commit -m "<commit message>" : if we want to avoid to open a text editor like vim/nano to add commit message we can use this command.

`git remote` : list down all the remote connections names.

Remote connections -> It helps us you to link two git repositories for uploading and downloading changes from each otherwise.

`git remote add <name of remote> <link of the remote>` : this command helps us to add a new link to the remote repo and give a name to it.

`git remote rm <name of remote> `: this command delete a remote connection.

`git remote rename <oldname> <newname>` : this command renames the remote connection

`git add <file1> <file2> <file3>` : This command will add multiple file changes together in the staging area

`git add . ` : this command will add all files from the working repo to the staging area.

Note : The name of the remote connection is always used to establish the communication between the repos.

`git pull <remote name> <branch name>` : Downloads latest change from branch of mentioned remote in our local repo.

###Recommended practice to do:
- Make changes
- git add <file>
- git commit 
- git pull
- git push

.
hello

merge conflict can occur if multiple people try to make change tu the same file, and then collaborate.

merge conflict are a very comman scenario

h
.