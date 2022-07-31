# Make a local folder into a repository
## You can also work the other way, start with the local and move to the online.

0. You can use git version control without the online component if you choose

1. git init
2. The easiest way to put this online is just to make an empty online repo
3. Copy the SSH URL
4. git remote add origin *SSH URL*
5. (Check) git remote -v
6. git push origin master (after all the usual stuff)


# Branching

1. git branch --> show the branches and stars the active branh
2. git checkout (-b) branch_name --> Use this to jump branches or make new ones
3. 