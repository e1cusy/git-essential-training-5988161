This is my content area
 By using the command git add NameOfNewFileAdded the changes will be staging letting git knows that I want the changes done in this file on my next commit. 
Another option is to use the command git add . which will stage all changes in the directory including any changes done in this file. 
Next. To add the changes from staging into the local repository the command git commit -m "Text explaining why am I commiting this changes" can be used.
Now to push our changes to the remote repository we use command git push This will make the remote equal to the local.
Use command git pull to bring changes in remote repository to the local repository.
If remote repository and local repository diverged then use command git pull --no-rebase origin NameOfLocalBranch to ensure bringing the remote changes to the local. A mesage for the merge can be added to the merge before hit commit. After the commit the changes from the remote should be available in the local.