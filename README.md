# This is my NewRepo Please note this is created from local and then pushed into remote repo 
# Steps : 
# 1.Created Folder NewRepo here 
# 1.   First of all create directory under your project 
# 2. Navigate to that directory . 
# 3. Now when you check by command ls -a you will get ./ ../ because it is not initialized with git yet 
# 4. 3rd Step is to check wheather that directoy is git repository or not .
# 5. Now to make that created directory as git repository we can make use command
  #  git init on that directory
# 6. After hitting $ git init command you will get below msg like this It means that your git repository has been created.
# Output--> Initialized empty Git repository in E:/Practice Program/gitdemonew/NewRepo/.git/
# 7. Now to check this just enter ls -a for that directory like below 
# output anike@Lenovo MINGW64 /e/Practice Program/gitdemonew/NewRepo (main): $ ls -a    
# ./  ../  .git/
# 8 .git/ is the indication of git repository has been created for newly craead folder NewRepo from local machine
# 9. Please follow point a) 
--------------------------------------
# a) Pushing your project work into new repository 

# Now you have created New Repository But to push the changes you need to created one remote repository on your website
# GO to New - Create Repository on your website 
# Now you have to commit all the code which is crreated under NewRepo 

# But before pushing your code to remote repository you need to add remote repo like below and also copy the link of new repository which you have created on your website 
# you will get link once you created remote repositoy on website Please refer below example 

# Command --->  git remote add origin <-link-> 
# Example   ---> git remote add origin https://github.com/aniket247/NewRepo.git
# here it means that we have to add new repo with name origin Please keep name as origin So here it will set our origin . Please hit command and check 
# To verify remote is set or not you can check by Command git remote -v    
# You will see current repo which you have set now that is NewRepo.
# Now check your branch (Check below point b) and rename (Check below point c)  then push your changes to NewRepo because all your changes in localhost this should go to remote repo which you created now
# -------------------------------------
# b ) To check branch which we are working on command git branch
 # branch means here developer teams working on development task backend team work on other task but with same code . So they both are making copies on their local with branch So that copy is branch. 
# ------
# c ) To rename our branch 
 # Please note that Master and main are different branch 
# Command git branch -M main  (To rename branch ) --- > Suppose you are having branch name as master then you can rename it to main by hitting above command 