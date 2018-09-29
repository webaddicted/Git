# GitCommand

**create a new repository on the command line**

    echo "# Test" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git remote add origin https://github.com/webaddicted/Test.git
    git push -u origin master


**push an existing repository from the command line**

    git remote add origin https://github.com/webaddicted/Test.git
    git push -u origin master

**create new branch**

    git checkout -b <branch-name>
    git push <remote-name> <branch-name> 

**switch on new branch**
    
    git checkout -f 

**get all branch**
    
    git fetch 

**get pull**
    
    git pull -f origin other-branch

