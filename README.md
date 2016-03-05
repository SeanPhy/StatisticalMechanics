# StatisticalMechanics


Tips for users:

Hello

You should know a little bit about what is Git and what is GitHub.
Use www.baidu.com if you feel that you are not clear enough about them.
<br>
<br>
1. Set up the project on your own computer:
--------------------------------------------

####1.1 Get your own GitHub account

####1.2 Download GitHub Desktop (https://desktop.github.com/) and install
        a brief introduction to it: (https://github.com/integrations/github-desktop)
        
        it will install a GitHub and a Git Shell
        GitHub is mainly used to visualize change history
        Git Shell is for version control and changes submit
####1.3 Accept invitation to the SM-at-THU team
        you should offer me your GitHub account name for me to invite you
####1.4 Clone StatisticalMechanics to your Git Desktop 
    
        by clicking "Clone in Desktop" button at the lower right corner on page 
            https://github.com/SM-at-THU/StatisticalMechanics
        or by clicking "+" button at the upper left corner on GitHub Desktop, then
            choose "SM-at-THU"(it should appear if you accept the invitation successfully), "clone", "StatisticalMechanics" and finally "Clone repository"(at the bottom)
            
        in both way GitHub Desktop will ask you to browse a path for you to put the clone of StatisticalMechanics.
            default path(C:\Users\<your account>\Documents\GitHub) is suggested
            
  
<br>
<br>

2. Using Git Shell
------------------

    Although GitHub Desktop offers functions such as publish and synchronize, they are not clear enough. 
    Sometimes you modified your file and clicked "sync" in GitHub Desktop, but the file remains unchanged on the GitHub website. So we need Git Shell.
    
    Introduction to some Git commands:
    
        (http://blog.csdn.net/chun799/article/details/9095635)
        
    Only commands listed below are usually needed:
    
####3.1 Open Git Shell and browse to the directory of project StatisticalMechanics
        if you clone StatisticalMechanics in the suggested path, you only need to input "cd StatisticalMechanics"
        
####3.2 Use 
    
                git status
                
        to check modified files, files not change and files Git didn't track
        There are usually three kinds of file status:
            Changes to be committed: files whose changes will be uploaded
            Changes not staged for commit: files changed but won't be uploaded
            Untracked files: files which Git didn't track their changes
            
####3.3 Use 
    
                git add <foldername or filename>
                
        to add folders and files from "Untracked files" and "Changes not staged for commit"
            to "Changes to be committed"
        you can use "*" for abbreviate, e.g., git add class* will add all folders and files whose name begin with "class" 
            
####3.4 Use 
    
                git commit -m "<some notes here>"
                
        to commit changes of files which are in "Changes to be committed"
        Be aware that after this command the changes is still local
        
####3.5 Use
    
                git push
                
        to submit your local changes online
        things on (https://github.com/SEhomeworkTeamUnnamed/StatisticalMechanics) should change now

####3.6 Use
                git fetch
        
        to get changes from website to your local repository
        better to use git status to check changes first

        
<br>
<br>

--by jwt 2016-2-29
    
