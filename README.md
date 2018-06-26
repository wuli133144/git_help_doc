# git_help_doc
git document
# git's step of work

#### first normal works need three branch at least
######  1 named  master
######  2 named  bug
######  3 named  feature

#### how to create a new branch
>just do it like this:<code>git branch "branchname"</code>,then a new branch is created ,you can 
>find it by using this command:git branch ,then you can get it; so easy
#### how to delete a branch of useless
> just using commands:git branch -d "branchname"
#### how to make relationship between local object and remote object 
>git checkout -b "local branch" origin/"remote branch"

#### how to show details of operations about branch 
>git show or git status 

#### how to update a branch 
>update a branch it's not easy ,first you shold get remote files,using commands <code>git pull or git fetch "branch"</code>
there is a notion that you had to forget git pull ,because it's dangerous to use ,i never use it ,then ,you should <code>
git merge "branch local"</code> util now your workplace is up to date,

#### how to push 
> first make sure your workpalce is lastest enough,otherwise it will fail when you push files,just using like this<code>
git push </code>
#### how to merge kinds of branch 
>just like this: <code>git merge "branch" </code>,if there is a trouble happend,just update all files ,be careful
#### others 
>remember to create three branchs ,if you follow my opinions ,your work will become so esay,on feature branch ,you had to do your mainly work
on bug branch ,you have to fix your bug in your programs,then if you finish all works,do't forget to delete temp branch,
>good habits is a good begin,good luck!




