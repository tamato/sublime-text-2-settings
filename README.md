my user settings for sublime text 2

list of packages
* GLSL
* hlsl
* move tabs
* package control (http://wbond.net/sublime_packages/package_control/installation)
* perforce
* theme - nil


Helpful website for git commands
http://rogerdudler.github.io/git-guide/


Git controls (if using GitBash):
    Add a file to git:
        git add <filename> 
            -- The cheap way is to use "git add -A", the -A is similar to "git add .; git add -u"
            -- "." = finds all new or modified files (does not remove any files)
            -- "-u" = finds modified files and removed files (does not add new ones)
    
    to commit to your local repo:
        git commit -m 'your message'

    to push those changes to the master shared repo
        git push origin master
            -- origin = the name of the shared repo
            -- master = the name of the repo on your machine