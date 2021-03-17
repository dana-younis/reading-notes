By utilizing a Version Control System (VCS), mistakes with files can easily be rectified.

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it,

All files in a checked out (or working) copy of a project file are either in a tracked ( can be modified, unmodified, or staged)or untracked state(currently reside in the staging area).

Stashing Changes: to  temporarily removes changes and hides them
The local Git repository has three components:

Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit