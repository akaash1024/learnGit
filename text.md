Git Angela

ON LOCAL SYSTEM  Vs GIT Bash
---------------------------------------------------
git bash > pwd > move to desktop

> git mkdir learnGit
cd learnGit
> git touch chapter1.txt
	**edit : in chapter1.txt > "Hello this is beautiful day"

> git init
	**this will create/track by git
	** .git created but its hidden and for that run,
> ls -a //show all files include hiden

> git add chapter1.txt || git add ./ "in case want to add everything instead of one by one"
> git commit -m "WHAT IS YOUR MESSAGE"
> git log "committed address, author, date and message too,
 
> touch chapter2.txt
> touch chapter3.txt

run > code chapter3.txt

> edit the files chapter 2,3 and add . and commit > git log

 > edit again , means mess the chapter3.txt data with "dumbo jumbo text"
	- want back those lost data back?!
> git diff chapter3.txt
	- this will show in detail

> git checkout chapter3.txt
	- as you hit this cmd chapter3.txt replace with old data


---------------------------------------
ON Web SYSTEM

GitHub.com > new repository > same name / whatever you want //NOTE use uncheck READ.MD 
after creating copy the repo link for remote

----------ON VsCode Git Bash
> git remote add origin htps://github.com/Anglesbagdhfhdshfsd
  - you have to paste your link there,
> git push -u origin main / git push origin main

----------ON web
> Repo > insight > Network




>>>>>>>>>>>>>>>>>>>>>>Git ignore

pwd > desktop > project >
touch first.txt, second.txt, third.txt, secret.txt

touch .gitignore
git init
git add .
git status
---- now mistaken initiated the secret files too,

lets reverse it,
> git rm --cached -r .

> git status //now all files are untracked


//want to commit all files except secret files. so,
open .gitignore > write that file name as it is, > secret.txt

git add .
git commit -m " commet"

---------------------------------------------

>>>>>>>>>>>>>Branch 
git branch testingGit //create branch
git branch  // chekc how many branch you have
git checkout testingGit //changing the branch from main to testingGit
		ps. git checkout -b testingGit // direct create and move to that new branch

git checkout testingGit
cd story > touch testingGit.txt & deleted more files // modification in "testingGit.txt"
git add .
git commit > git log

now you can checkout main and find there is not change in main branch files. 

in main branch
*main 
touch akash.txt //modifiying / add . / commit 

git checkout testingGit
akash.txt not exit here


---------------------------------------------

>>>>>>>>>>>>>Merge

git checkout main
*main
git merge <branch name> //  git merge testingGit 
	**open vim text editor
	***simple give merge message or typw :q!

git push origin main -u


DONE.................................

