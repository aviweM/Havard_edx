/usr/bin/bash
- www.github.com/new (To creat a new repository)
- Take the HTTPS link to actually clone the repo, on your local computer (this is done on the terminal)
- e.g git clone https://github.com/aviweM/Havard_edx.git 
- touch hello.html to create an html file (Add the content you would like inside this file)
- To push the content from git to github:
git add hello.html (name of the file)
git commit -m "Add line" (git keeps track of inserted and deleted lines)
git push (publish to the server or host which is github) 
- To see the web content, type: start hello.html (it will display on a browser)
- git status (to see the branch you are working on, and the updates)
- If a collaborator edits files inside of github interface, then you must use git pull, to acccess data from github.
- To resolve Merge conflicts, compare your edited version and the remote one. Decide which changes you want to keep and commit changes.
- git log command will actually give you te reference of all your commits including author and when changes were done.
- git reset --hard <commit> (revert changes using the last commit)
  git reset --hard origin/master
- Use branching incase yiu encounter a bug,one branch can be about fixing bug while on the other branch you can add new features for the project. Then merge them once youve fixed the bug
- git branch command, will tellyou the branch youre working on
- To switch to a new branch, git checkout -b new_branch_name 
- git commit -am "Text", if you use thiscommand you do not have to use git add
-git fork - is when you fork a repo on github, clone it to your computer, make changes, and push your changes or modified changes to your fork(you can optionally submit a pull request to the original repo)