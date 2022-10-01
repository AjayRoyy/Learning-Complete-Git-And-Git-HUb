
this is a complete learning tutorial for git and git hub

till now i have learned how to add file by using git
commad for add file into the staged environment we will be using command "$ git add".
examples
	git add file.name
	git add --all (TO add all file to the staging area)
	git add -A (shorthand form of --all,this will also add all the file to the staging area)
	git add . (this will also add all the file to the staging area) (just a another short hand form)


now i am at a stage where i can commit all the files that i added to the staging environment or staging area

commit command example
	git commit file.name
	git commit -m "Enter the message here"

IF we want to commit directly without adding to the staging area or environment we can use this command "-a"
	git commit -a -m "Enter the message here";

If we want to delete a branch after merging with the master branch we can use the command (-d)
	git branch -d BranchNAme
