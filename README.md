# GitCommand

**create a new repository on the command line**

    echo "# Test" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin
    git remote add origin https://github.com/webaddicted/Test.git
    git add .
    git push -u origin main // master

**Change remote url**

      git remote set-url origin https://webaddicted_migos_inson.git

**Check Remote URL**

        git config --get remote.origin.url

**push an existing repository from the command line**

    git remote add origin https://github.com/webaddicted/Test.git
    git push -u origin master

**create new branch**

    git checkout -b <branch-name>
    git push -f origin <branch-name> 

**switch on new branch**
    
    git checkout -f 

**get all branch**
    
    git fetch 

**get pull**
    
    git pull -f origin other-branch
    https://github.com/wsdesignuiux/Android-ui-templates
    https://github.com/superdevzhao/beautiful-android-ui

**Get Line of code from to date**

    git log --since="2024-04-01" --until="2024-04-30" --pretty=format: --numstat --author=deepaksharmatheboss@gmail.com     | awk 'NF { add         += $1; del += $2 } END { printf "Added lines: %s\nDeleted lines: %s\nTotal lines changed: %s\n", add, del, add + del }'
    
    Output is
    
    Added lines: 769987
    Deleted lines: 572195
    Total lines changed: 1342182

## WIFI ADB Connect :

1. Add adb path in environment variable like **C:\Android\sdk\platform-tools\adb.exe**
2. In cmd in project path call **adb shell ip route**
3. **adb connect 192.168.33.17:5555**
