# Class 3 Reading Notes

In this section for reading notes we will be learning about Git.

## References 

https://blog.udemy.com/git-tutorial-a-comprehensive-guide/

## Lesson Breakdown

### What Is Version Control?

Version Control or VCS is a system that helps you track, revisit, or if necessary revert back to different versions of your code. It also allows you to collaborate with other users and developers and if need be see who made changes and when. Version Control can be considered a fancy Google Drive for web developers.  

### Understanding Local Version Control

Local Version Control is a database on your local computer hard drive that stores every file change.  

### The Need For Centralized Version Control

Centralized Version Control or CVCS is a system that offers software developers and software development teams the opportunity to collaborate on projects using a central server instead of involving all local databases.  

### The Purpose Of Distributed Version Control

Distributed Version Control or DVCS is a system that brings or allows the user to create mirrored repositories on every team member or users computer as a local copy. By doing this, this addresses the majoy vulnerability of Centralized Version Control or CVS because if a CVS was to stop working, team members and collaborators wouldn't be able to work with each other on a file, or save changes and new versions of a file.  

### What is Git

Git is a Distributed Version Control System or DVCS that stores and track changes in a project file, these are saved as a snapshot. Everytime the user saves a changed version of a project which is also known as commit, Git creates a snapshot of thaat file and stores a reference to it.

#### Local Operations

Git for the most part relies on local operations, because most of the files and resources that Git needs can be found in the local resources. This also allows for convenience because since the project or project's history is on the local disk, Git doesn't have to fetch history and other information from the server. This also allows the user to work on different projects even when the user isn't online or using a VPN.

#### Tracking Changes

Git has been created to track any and every single change that is applied to any file or directory. Because of this Git will always detect file corruption or loss of information in transit.

#### Loss Of Data

Git was created to greatly reduce the possibility of irreversible damage to files that the user has such as accidentally lost data. Git makes it difficult for snapshot of your file that has been committed to be lost.

#### Understand The Three Main States

Git Files can reside in three main states: Committed, Modified, and Staged.

1) Committed - Data is securely stored in a local database.

2) Modified - File has been changed but not committed to the database

3) Staged - Flagged a file's changed version to be committed in the next snapshot.

### The History Of Git

Git roots are traced down to the open source software project Linux Kernel. In 2002 developers of this project began using a Distributed Version Control System or DVCS called Bitkeeper. But in 2005 many of these developers actually stopped using this DVCS due to the tension between the Linux kernel community and the company behind BitKeeper's and the eventual revocation of the DVCS' gratis status. After all of this took place, Linus Torvalds, the chief architect of the Linux kernel, began creating Git. With the purpose of creating a DVCS with a similar workflow deisgn to BitKeeper. Git allowed for non-linear development via multiple branches, could support large projects, possessed strong mechanisms preventing corruption, and also had a simple design. Since its creation in 2005, Git has become of the most popular and utilized Version Control Systems in the world.

### Downloading Git On Mac OS X

#### Download Git

In order to use Git, The user computer must have it available. If the user already has Git on their computer, The user should make sure they have the latest version. 

Git can be installed in three different ways:

1. Install as a package
2. Install via another installer
3. Download and compile the source code.

##### Terminal

The simplest method for installing Git on a Mac (for Mavericks 10.9 and above) is running Git from the Terminal. If Git is not installed on the users mac, The user will see a prompt for installation in the terminal.

##### Git Website

The user can also download Git by visiting the link below, and following the posted directions.

http://git-scm.com/download/mac 

##### GitHub 

Another option is to install Git as part of the Github for Mac install. GitHub is repository hosting service. 

The User can download GitHub for Mac with this link: http://mac.github.com


### Download Git On Windows

Git Website

You can download Git by visiting this link and following the posted directions:

http://git-scm.com/download/winLinks

GitHub

Install Git as part of the GitHub for Windows install.

http://windows.github.com

### Graphical Clients

Git includes inherent Graphical User Interface (GUI) tools. The user can also utilize third-party tools.

GUI Clients

You can access a variety of GUI clients for Mac, Windows, and Linux using the following link below:

https://git-scm.com/downloads/guis


### Things I want to learn more about

I trully want to learn everything I can to fully master Git, of course to have a good understanding of it, will take time.