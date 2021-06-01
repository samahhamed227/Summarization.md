# Git 

**it is highly recommended that you have 
a solid understanding of the Terminal (for Mac) 
or Command Line (for Windows and Linux).**

### Version Control
Version Control is a system that 
allows you to revisit various versions
 of a file or set of files by recording changes.

- Git is a DVCS that stores data in a file system
 made up of snapshots. Each time you save 
a changed version of your project — called commit —
-  Git creates a snapshot of the file and stores 
a reference to it. If the file has not changed,
-  Git only stores a reference to the already-stored 
identical version of it.


1.Loss of Data
Git is set up to greatly minimize the possibility
 of irreversible damage to files, such as accidentally
 lost data. Git makes it extremely difficult for a snapshot
 of your file that is committed to be lost.
2. States
Files in Git can reside in three main states:
 committed,
modified and staged.
3.Committed
Data is securely stored in a local database
4. Modified
File has been changed but not committed to the
 database

After installing Git,
 users should immediately set 
the user name and email address, which will be used for every Git commit.
Type the following into Terminal or Command Line

Local Repository Structure
The local Git repository has three components:

Working Directory: The actual files reside here.
Index: The area used for staging
Head: Points to the most recent commit

