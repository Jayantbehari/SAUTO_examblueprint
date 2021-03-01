# SAUTO_examblueprint
Git commands are divided in high level ("porcelain") and low level ("plumbing ") commands.

* porcelain:
	git-add < add file contents to the index.>
	git-am 	< apply a series of patches from a mailbox.>
	git-archive < create an archive of files from a named tree.>
	git-checkout < switch branches or restore working tree files.>
	git-clone <clone a repository into a new directory.>
	git-commit <record changes to the repository>
	git-diff <show changes between commits, commit and working tree, etc.>
	git-grep <pring lines matching a pattern.>
	git-init <create an empty git repository or reinitialize an existing one.>
	git-merge <Join tow or more development histories together.>
	git-push <update remote refs along with associated objects.>
	
* Plumbing <prilemanary for scripted use, goes deeper than porcelain, plumbing is for advanced users>
	git-apply <apply a patch to files and/or to the index.>
	git-commit-tree <create a new commit object.>
	git-mktree <build a tree-object from ls-tree formatted text.>
	

git help config <gives more help regarding the config section>

1.1.3 === To initialize a new git repository ===

cd to the folder of your new project.
$ cd desktop/cafe_recipes
$ git init <creates a hidden .git directory. Go to this folder cd .git then ls gives a list of files and folders in the .git directory
remember that the .git directory contains all the git meta data for the newly created project.

We have now intalled git, initialized git and added files to our git project as a git repository.
The files are now version controlled by git, arnd are ready to be4 tracked of any changes to be made.

But as all this is only local at our local desktop computer this project can only be updated from the local computer
To solve this we can host this git repository in an online cloud-like setting.

GITHUB <online GIT repository hosting>
