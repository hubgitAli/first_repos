git  / show all commands

git init / create a repasitory or valume

git status / show the status of our file and show us where of our code changed an is not commit

git add (file name or . ( 'dot' means all)) / add our changed files  , here it add to stage , and stage is a place between our root code and repasitory / in first time most use 'add'

git rm ('remove') --cashed -r .('dot' means all) or 'our file name'  /  it uncashed data or remove data from stage that we add by add command

git commit -m 'our comment'  / here we can write our comment , specialy when make a change to other person find out what happend

git commit or git commit -a -m 'our comment' / move stage data to repasitory / i can mean the commit as 'ghadam' 😊

git diff  / show us the change (diffrent)

when we type 'git diff(or any command) --help'    /  it show you all command inside the diff or any command that is there

git log  / give us the log of commit(comment) that we create
git log --oneline / show the logs in better view

git log -1 --oneline  /show the last log 

git log -2 --oneline / show the 2 last log

git log -p  / show the log of changes in evry  commit

git log --stat

git checkout -- . ('dot' means all or i can use file name)  / this return my file to perevius commit data (it work befor i commit in stage)

git reset head (file name or dot like other commands)  / its return my changed file to perivios version in to stage like checkout command but show us the changes and data / in other word if we wanna checkout , firs need to reset head and then checkout 

git reset commit_id  / if i want to back to a old commit i can enter git log commit and then take the id of commit and give it to git reset 

git reset --hard 'id'  / when we add some file in our directory , and then add them an then reset them by git reset head id , here the file root that we add like folder or fil will not delete so we use git rest --hard id to reset file in root

git reset soft --id 

git branch --help / show all command in browser

git baranch --h  / show all command in git bacth

git barnch (branch_name)  / make a branch to create another version than our app / note : befor create a branch , ge a status so if u have changed file thao not add , so add them and then make a branch

git branch -a  / show us all our branch

git checkout (our_branch_name)  / when we create a branch and wanna sitch to  it we use than this command

git branch -d (our_branch_name)  / we can delete our branch , note that we can not delete branch that we ar using now

git checkout-b (branch_name)  / we can create a branch 