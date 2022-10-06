+ Blog Article (2-3 paragraphs with code sample)
+ Dictionary / Flash Cards
+ Notes in outline form
+ Fill-in-the-blank worksheet of key concepts

# Revisions and the Cloud

+ Version control - sysmte that allows users to revisit revised versions by recording chagnes
+ What is git? Distributed version control system that stores data in  a file system made up of snapshots
+ Three states of files in git: Committed, modified, and staged
  + Committed - Securely stored
  + Modified - File ahs been modified but not committed
  + Staged - Flagged a file's changed version tob e committed in the next snapshot

## Getting Started with Git
+ Download Git and install as a package, another installer, or compile the source code.
+ MacOS- follow instructions from [Git webiste](http://git-scm.com/download/mac) or [Github](http://mac.github.com)
+ Windows - follow instructions from [Git webiste](http://git-scm.com/download/mac) or [Github](http://mac.github.com)
+ Git Config - allows setting of configuration variable sthat constrol aspects of GIt's operation and look
+ Identity Setting - Set the user name and email adress which will be used for every Git committ
  + git config --global user.name "Jane Smith"
  + git config --global user.mail "example@email.com"
+ You can change text editor by typing the following command line
  +  git config --global core.editor [name of text editor]
+ git config --list : check setting
+ git help command : get more infrmation of a particular command
+ cd test : switch to the target project's directory 
+ git init : created new subdirectory
+ git add \*.c, git add LICENSE, git commit -m"any message here" : starts tracking repository files, perform an initial commit
## Cloning
+ git clone https://github.com/test : creates a copy of an excisting Git
+ git cloe [url] mydirectory: clones a repository into a directory

## Workflow
+ git add filename, git add* : track one file, all files in a repository
+ git commit -a : commits a snapshot of all modifications
+ git push origin master: push changes to a remote repository from the local master branch
+ git stash: ready to commit changes but not want to lose them either, this command temporarily removes changes and hides them

## Remoted Repositories
+ for cloned repositories, Git will automatically give the name origins to the server from which you cloned and the name master to your local branch
+ git remote: view the short names of all specified remote handles
+ git remote -v: view all the remote URLs next to their correpsonding short names
+ git remote add shortname url : create a new git repository with ashort name
+ git fetch [remote -name] : pulling data that you don't have from a remote project, solely pulls new data to a local repositorym, it does not merge changes with or modify your local work
+ git fetch origin: pull down any new changes from cloned repositories
+ git push [remote-name][branch-name] : push changes upstream for sharing, this command pushes committed changes from you local master branch upstream to the origin server
+ 
