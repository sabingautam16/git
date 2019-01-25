# git commands *=optional 



Set Name in Git:                                    git config --global user.name "John Doe"
Set E-mail in Git:                                  git config --global user.email johndoe@example.com
View Entered Settings:                              git config --list
Initialize Git Repository:                          git init
Create Local Copy of Existing Git Project:          git clone <path>
Add File to Commit:                                 git add <filename>
Check Status of Files Before Commit:                git status
Take "Screenshot" of Changes to Local Repository:   git commit       (git will ask for message)
                                                    git commit -m "<message>"
Make new Branch:                                    git branch <branchname>
Change Current Branch or Load a Saved Commit:       git checkout *-b <branchname> 
                                                    git checkout <commit>
Merge Branch Into Current Branch:                   git merge <mergedFromBranchName>
See Relationship Between New and Parent Commits:    git log --oneline --graph
Add Remote Repository:                              git remote add <name><url>
Add New Commits to Remote Repository:               git push *<remote_name>*<local_branch>:<remote_branch>
Update Remote Branches With Most Recent Commits:    git fetch <remote_name>
Fetch Immediately After Adding Remote Repository:   git remote add -f <remote_name><url>
Create Local Branch With Same Commit History As 
  Remote Branch:                                    git checkout -b <local_branch><remote>/<remote_branch>
Make Branch a Tracking Branch (when pushing):       git push --set-upstream <remote><remote_branch>
Update Current Branch:                              git pull *<remote>*<remote_branch>
Make an Alias:                                      git config --global alias.<alias_name> '<command>'
Delete Alias:                                       git config --global --unset alias.alias_name
Check Current Aliases:                              git config -e --global
