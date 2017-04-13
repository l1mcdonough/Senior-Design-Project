Quick git notes
===============

Hey my friends working on this project! so, here is how to commit, or add, your changes to the repo, and push them to the repository so we can ALL see them :)
0) remember to pull any changes from OUR remote repo before starting to code! `git pull ourversion master`. if you want to pull changes from the original repo,: `git pull origin master`
1) add your code changes! 
This is pretty self explanatory. Code as much as your little heart desires. One thing to note tho is, you should commit small changes and commit OFTEN. 
2) Commit those changes
once you have added your changes, commit them LOCALLY first! 
    a) add them to the "staging area"
    `git add .` which will add ALL changed files to the staging area or, you can specify the file: `git add filename.java`
    b) `git commit -m "commit message goes here"`
3) run `git pull ourversion master` before pushing
4) git push those changes to OUR remote repo like so `git push ourversion master`. if you get a merge conflict, read my powerpoint on how to resolve them or just google it, man.