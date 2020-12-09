# Revisions and the Cloud

Version Control - system (VCS) that records changes and allows the user to review previous versions of a file
 - Local VCS -one database on your hard disk that stores changes to files
 - Centralized VCS -one server storing all changes and file versions, is accessible by various clients, and allows for collaboration. With CVCS there is risk of the server being the single point of failure if it goes down or is corrupted, possibility of catastrophic loss
 - Distributed VCS -prevents catastrophic loss by allowing clients to create mirrored repositories, seperate backups that can be used to replace lost information. Allows various simultaneous workflows.

# Git

Git is a DVCS that stores data in a file system made up of snapshots. Everytime you commit a change, git creates a snapshot of the file and stores a reference to it

Local Operations
Git relies on local operations, a projects history resides on the local disk, this allows work offline or on a VPN

Tracking Changes
Every change applied to a file or directory is tracked by Git. Git will always detect file corruption or loss in transit.

Loss of Data
Git is set up to greatly minimize damages to files and prevent losses of snapshots

Three main states of Git files
 1. Committed -data securely stored in local database
 1. Modified -file was changed but not committed
 1. Staged -flagged a file's changed version to be commited in the next snapshot

> Git was created by Linus Torvalds in 2005 and has become the most utilized Version Control System in the world.
