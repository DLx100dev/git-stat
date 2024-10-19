
# git-stat.sh

 - Simple bash script for getting some info while having many versions of git in WSL. 
 - It prints git system executable, its alias if existing, repo status, credentials, branches and remotes.

 ## Usage

 - `chmod +x git-stat.sh`
 - `./git-stat.sh`
 - Tou launch it from any place by just `git-stat` do `sudo cp git-stat.sh /usr/bin/git-stat'
 - It is intended to be used with default `git` command in your command line and with `gh` Github cli application. 
 - If you need to use mingw git, windows git or some other instead of WSL (if installed), add `alias git=[your git]` in ~/.bashrc, if not needed you can comment it with `#` later.
 - You can uncomment some lines to make output more verbose.
