`git init` - power your folder to be managed by git and created a new empty repository . it also create a .git folder that holds all relavant logic to manage versions of your project.

`Working area` - There can be a bunch of files that are not currently handled by git; it means that changes done or to be done are not managed by git .A file which is in the working area is not considered to be in the staging area.When we do git status and we see a bunch of untracked files then these are actually called to be in the working area.

`Staging area` - what all files are going to be part of the next version that we will create. This staging area is the place from which git knows what changes will be done from last version to next version.

`Repository area` : This area actually contains the details of all your previous registered versions.whenever we registered a version all of that data is stored in this area. All the files in this area git already manage them and know their version history

`git add <file>` : this moves file from working area to staging area.

`git rm --cached <file>` : moves file back from staging area to working area.

`commit` : commit is a particular version of the project . It captures the Snapshot of the project staged changes and creates a version out of it

`git commit` : registers staging changes to a commit.

`git log` : lists down all the commits of the repository.If you want to exit out of git prompt press `q`.

`git restore <filename>` : it remove all files changes from the staging Area to be committed. This can be useful , if we did some dirty pieceOf code and now no more want it instead of deleting every change Line by line we can restore or we can say restore last version of the file

hello 

shubham