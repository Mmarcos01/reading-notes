[Home](README.md)

## Revisions and the Cloud

Version Control - system (VCS) that records changes and allows the user to review previous versions of a file
 - Local VCS -one database on your hard disk that stores changes to files
 - Centralized VCS -one server storing all changes and file versions, is accessible by various clients, and allows for collaboration. With CVCS there is risk of the server being the single point of failure if it goes down or is corrupted, possibility of catastrophic loss
 - Distributed VCS -prevents catastrophic loss by allowing clients to create mirrored repositories, seperate backups that can be used to replace lost information. Allows various simultaneous workflows.

## Git Intro

Git is a DVCS that stores data in a file system made up of snapshots. Everytime you commit a change, git creates a snapshot of the file and stores a reference to it

#### Local Operations
Git relies on local operations, a projects history resides on the local disk, this allows work offline or on a VPN

#### Tracking Changes
Every change applied to a file or directory is tracked by Git. Git will always detect file corruption or loss in transit.

#### Loss of Data
Git is set up to greatly minimize damages to files and prevent losses of snapshots

#### Three main states of Git files
 1. Committed -data securely stored in local database
 1. Modified -file was changed but not committed
 1. Staged -flagged a file's changed version to be commited in the next snapshot

> Git was created by Linus Torvalds in 2005 and has become the most utilized Version Control System in the world.

### Git Command Notes

#### Identity 
Set the user using the following:

git config --global user.name "Jane Smith"
git config --global user.email "example@email.com"

#### To confirm user use:

git config --global user.name (should return Jane Smith)
git config --global user.email (should return example@email.com)

**With the –global option, the settings apply to anything on the system. To use different identity settings for a specific project, change the working directory to the desired local Git repository and use the commands without using –global.**

#### To configure a different text editor: 
$ git config --global core.editor "texteditorname"

#### To check settings:
git config --list

#### To get help with a command:
git help command
git command --help
man git-command

#### Importing:
 1. $ cd test (switch to project's directory)
 1. $ git init (create new subdirectory named .git that has the repository files)
 1. $ git add *.c
$ git add LICENSE
$ git commit -m “any message here” (starts tracking and performs an initial commit)

#### Cloning:
$ git clone https://github.com/test -create a copy of existing Git repository using the url

$ git clone https://github.com/test mydirectory-clone a repository into a directory with another name, makes a copy of the target repository in a directory named “mydirectory.”

#### Check file status:
$ git status

#### Track one file:
git add filename

#### Track all files:
$ git add *

#### Commit file:
$ git commit -m “made change x,y,z”

#### Commit all changes:
$ git commit -a

#### Push changes:
$ git push origin master

#### Stashing changes:
git stash (temporarily removes changes and hides them)
git stash apply (retrieves hidden changes)

#### Local Git repository has 3 components:

 1. Working Directory: where the actual files are
 1. Index: area used for staging
 1. Head: points to the most recent commit

[More Information](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7_2)

[Home](README.md)
