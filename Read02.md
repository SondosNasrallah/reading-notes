# Git Tutorial: Summarization
### Getting Started with Git:
- Download Git
  1. Install as a package
  2. Install via another installer
  3. Download and compile the source code.
### Downloading Git Website (Windows):

[You can download Git by pressing this link](http://git-scm.com/download/win)

### Initial Customization
  After making sure Git has been installed, you should perform some customization steps, which should only need to be completed once on any machine.
  
  
  
  ### Setting up a Git Repository
   - Importing
     1. Switch to the target project’s directory
     2. Use the git init command
     3. To start tracking these repository files, perform an initial commit
    - Cloning
     By cloning the file, you have copied all versions of all files for a project.This command leads to the creation of a directory called “test,” with an initialized .git              directory inside it, which has copies of all versions of all files for the specified project. The command also automatically checks out a copy of the newest version of the        project.
     
     
   ### Workflow
   - Local Repository Structure
   
     ![Local Repository Structure](https://image.slidesharecdn.com/gitbranchstregagycasestudywoogenius-140314152231-phpapp01/95/git-branch-stregagy-case-study-2-638.jpg?cb=1413975847)


### Saving Changes
   - Tracked 
     Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.
   - Untracked 
     files were not in the last snapshot and do not currently reside in the staging area.


### The Life Cycle of File Status

   ![Life cycle](https://files.speakerdeck.com/presentations/238e9010b7930131988a16de6c2ebfa3/slide_11.jpg)
   
 ### Check File Status
     To determine the state of files, utilize the git status command:
     
       "$ git status"
       
 ### Committing a File
     After staging one or multiple files, you should commit the changes and record what you did within the commit message:
     
       "$ git commit -m “made change x,y,z”"
 ### Committing All Changes
 
       "$ git commit -a"
 ### Pushing Changes
     Next, you would push changes to a remote repository. We will discuss remote repositories in more depth in the next section. For now, we will look at a general overview of        pushing changes to remotes.
     Example:
     
     "$ git push origin master"
     
     
 ### Remote Repositories
   Cloned Repositories
   
    As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.
  
  Seeing Your Remotes
    1. By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles. 
    2. By using git remote -v, you can view all the remote URLs next to their corresponding short names.
  
  Adding Remotes
      To create a new remote Git repository with a short name, use the following format:
    
      "git remote add shortname url"
      
 ### Fetching
    Fetching entails pulling data that you don’t have from a remote project.
    Here is the command format:
  
    "git fetch [remote-name]"
  
  ### Pushing
    To push your changes “upstream” for sharing, you would use the following git push command format:

    "git push [remote-name][branch-name]"
    
  ### Renaming/Removing Remotes
   -Rename

      To rename a remote’s short name, use the git remote rename command.
     
   -Remove

     To remove a remote for whatever reason (e.g., a contributor has left the team, the server has moved), simply use the git remote rm command.
   ### 
