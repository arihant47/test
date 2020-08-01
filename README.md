# Pushing code to GitHub from goormIDE/Command Line [Using HTTPS]
  1. Create a new Repository   
  [NOTE: Uncheck " **Initialize this repository with README**" if it's already checked]
  
  2. Copy the HTTPS link which is automatically generated by GitHub.
  
  3. Open Git Bash terminal or your goormIDE terminal, go ahead and **cd** into the directory whose files you need to upload.
  
  4. Use the following commands -->
  > $ git init    
  > $ git remote add origin **Copied HTTPS link here**   
  > $ git remote -v **(To check whether the files have been uploaded correctly to the HTTPS)**    
  > $ git add **file name**    
  or simply git add . **(To add all the files of the directory)**   
  > $ git commit -m "Initial Commit"   
  > $ git push origin master       
  
  Go to the GitHub page and refresh it and **BOOM!** your repository has been uploaded