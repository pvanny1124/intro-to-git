#initialize git in a directory
    git init

#Add files to staging area
    git add <filename>

#remove files from staging area
    git reset HEAD <filename>
    
#add files of a certain type to staging area
    git add *.<extension>

#add all files to staging area
    git add -A

#commit 
    git commit -m "<message>"
    
#see whats tracked/untracked

    git status

#check the history of commits
    git log

#create hidden files
    .<name>.<extension>
    
#gitignore
    create .gitignore and write files in this that you want to ignore from staging area
    
#Git branches

    #list all branches
        git branch
    
    #create a new branch
        git checkout -b <name of branch>
            -switches to new branch automatically
            
    #switch branches
        git checkout <branch-name>
        
    #merging branches
        git merge <branch you want to merge>
        
    #removing branches
        git branch -d <branch to delete>
        
#linking github
    git remote add origin <url to repository>
    
    #check if the origin was added
        git remote -v
        
    #push to github
        git push -u origin <branch>
        
        
        