 **Git Commands and Terminology** 

   **Repository**

   *Repository* by definition is a place or object where things are stored. What a git repository is; is a file locationwhere you can store all of the files that relate to a current project. There are series of commands that can manage and organize this *repository*, but to create a git repository the following code is used;

      git init [project-name] 

The above command is used for creating a local respository on your machine with a specified name. 

   **Clone**

   *Clone* is a copy of the project that is in the respository that you can edit on your local machine. In order to use clone a URL is required from GitHub linking to a respository. An example of a url needed would be similar to this: https://github.com/Wve-program/Mini-Project01.git. Using git commands in order to copy the project and its entire current version would be:

     $ git clone https://github.com/Wve-program/Mini-Project01.git 

This code allows the user to create a clone of the project directly from the respository. You can sync both the locally created repository and the remote repository to transfer whatever changes that are performed on the local using commands. 

   **Fork**

   *Fork* is a copy of a repository that allows you to make two way changes. What this means is, is that another individual can be marked as a collaborator and work on the same project as you. Similar to cloning where they can copy the repository, but the difference here is that the person who is the Forker can only see Forks. The individual who is forked can use *pull requests* in order to contribute to the original project. On Github the individual who owns the project can't get forked themselves from the same repository. 

   **Branch**

   *Branch* is similar to that of a branch off of a tree, in this case, it is actually created when a commit is performed and designated as the *master*. Branches continue to expand the more commits/changes are peformed to the trunk/original project. Occasionally there are two branches that maybe similar and are required to merge together. Gitflow workflow will show the merging of these files or the histories of one branch into a currently selected branch. The following commands are necessary in order to utilize branch: 
     
     $git branch
     
     Lists all Local branches in the current repository

     $git branch [branch-name]
     
     Creates a New Branch

     $git branch -d [branch-name] 

     Deletes the specified branch


   **Commit**

   *Commit* command is used when changes need to be saved to the local repository. More the often there might have to bechanges to the project that are required. For instance, a *Patch* for a program is essentially for fixing a bug in the software or updating a program. Commits offer the opportunity to adjust the project, make the change and then push it to the repository. The following commands are used when and individual is looking to utilize *Commit*:

     $git commit -m "Fix: Issue with bolding"

This command saves the changes while -m sets a message for the commit just made to reference what has happened.

     $git commit -a 

This command includes all the currently changed files in this commit. 

     $git commit --amend

This command rewrites the very last commit that was made. Git will rewrite the last commit and replace it with the newly amended one. 


   **Merge**

   *Merge* it is a command that will combine multiple commits that were made together. *$git merge* will combine two branches together. If you have two branches that are looking to be merged the following commands are used:

     $git checkout master
    
     $git merge feature

The commands that are shown here state the following; Git Checkout focuses on the branch that will receive the merge while git merge feature is the branch that will be merged into the master. 

   **Checkout**

   *Checkout* shifts the focus to different branches in the project. When a branch is focused on using checkout it tellsGit to make all new commits on this branch. For example;

     $git checkout master
     
As previously stated the *Master* is now focused as all commits will be recorded on this branch.

     $git commit -m "Fixed: Error"

The very next commit would be recorded on that branch. It may come up at some point, but you could use checkout to highlight a branch to be merge with another branch as previously identified.

     $git checkout master

     $git merge feature


