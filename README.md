# git-and-git-hub-practical-
for my study notes
git --version                                    [ for checking git version ]
git config --global user.name "desai Nikita"     [ for setting user name ]
git config --global user.email "nikitadesai1126@gmail.com"    [ And Email Address ]
git config --list                                           [ listing of what you setting up user and user name ]   with credential helper who is store your credential 
 git clone https://github.com/desai-nikita/study-practical-.git                     [ for copy on your local system ]
 cd .\study-practical-\                              [ for change directory to folder ]
git status                                      [show git status] 
after modified file you should follow two steps 
git add  .                                     [ adding all  git file to staging area ] 
git commit -m " "                                [ git commit with -m means message for what you modified in your code ]
Your branch is ahead of 'origin/main' by 1 commit.    [ means your local change 1 step ahead as comparison git repo ]
  git push origin main                              [ upload local repo content to remote repo ]
  git init                                         [create a new git repo ]
 git remote add origin < https link>               [add new repo ]
   git remote -v                                  [ to verify remote]
  git branch                                      [ to verify which branch on you ]
  git branch -M main                               [to rename branch ]
  git push -u  origin main                         [ shortcut for git push origin main next time you type only git push  -u means to get upstream ]
  git checkout <branch name>                         [to switch another branch ]
  git checkout -b  <  to create new branch  ]
git branch -d  < branch name >                        [to delete branch ]   when you are on that branch you do not able to delete to this branch 
git diff <branch name >                             [compare between 2 branch commits files and more ]
git merge <branch name >                            [to merge 2 brancehs ]
create PR                                               [ it tells you tell others about changes you have pushed  to a branch in repo on github }
git pull                                                  [ used to fetch  and download content from remote repo and immediately  update the local repo to  match that content ]
git merge  conflict                                    [   two persons change on same line git is unable to solve this so you can do this manually  ]
git fork                                               [  copied someone repo to my repo ]
git reset  <file name >                              [ add but not commit ]
git reset                                               [ all reset ]
git reset HEAD-1                                    [by mistake  commit ] 
git reset <cmmit hash >                               [multiple commit back]
git reset -hard <hash >                           [ clear git and visual sudio also ]
git ignore < file name >                          [  ex for exmaple  3 credentials hide in file  but when you commit file you see only 1]
git log since and until                           [specific date till show log ]
git author ''                                      [specific user log ] 
git diff --cached                                 showing   by mistake what changes you do in file this file add also 
git restore --staged .                              back to staged area 
git restore .                                          correct changes 
git clean                                           untracked file clean
git tag -a <name>                                       provide name 
genearate pull request                                  A Git pull request is a way to tell others about changes you’ve pushed to a branch in a repository. Here’s a simple explanation:

You Make Changes: You work on your own copy of a project and make changes to the code.
Request Review: When you're ready for your changes to be added to the main project, you create a pull request. This is like saying, "Hey, I’ve made some updates. Can you check them and add them to the main project?"
Review and Discuss: Other team members review your changes, discuss them, and suggest improvements if needed.
Merge Changes: Once everyone is happy with the changes, they are approved and merged into the main project.


  
  
