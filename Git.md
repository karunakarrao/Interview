#### 1Q. What is GIT?
GIT is a open-source distributed version control system and source code management (SCM) system. it can handle small and large projects with speed and efficiency. Developer can have a local copy in which they can do changes and push it to remote repository by commiting the code. its written in C language

#### 2Q. What is a repository in GIT?
A repository contains a directory named .git, where git keeps all of its metadata for the repository. The content of the .git directory are private to git.

    HEAD/: A pointer structure used in git.
    Config/: Contains all configuration preferences.
    description/: Description of your project.
    index/: It is used as a staging area between working directory.
    object/: All the data are stored here.
    logs/: Keeps record to change that are made.

#### 3Q. What is the command you can use to write a commit message?
$ git add . ; git commit -m "commit message"
$ git add . && git commit -m  " commit message"

#### 4Q. What is the difference between GIT and SVN?
   
#### Q. What is “Staging Area” or “Index” in GIT?
Before completing the commits, it can be formatted and reviewed in an intermediate area known as ‘Staging Area’ or ‘Index’.

#### Q. What is GIT stash?
GIT stash takes the current state of the working directory and index and puts in on the stack for later and gives you back a clean working directory.  So in case if you are in the middle of something and need to jump over to the other job, and at the same time you don’t want to lose your current edits then you can use GIT stash.

$ git stash
$ git stash list
$ git stash drop

