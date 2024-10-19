
# git-stat.sh

 - Simple bash script for getting some info while having many versions of git in WSL. 
 - It prints git system executable, its alias if existing, repo status, credentials, branches and remotes.

 ## Usage

 - `chmod +x git-stat`
 - `./git-stat`
 - Tou launch it from any place by just `git-stat` do `sudo cp git-stat /usr/bin/git-stat'
 - It is intended to be used with default `git` command in your command line. 
 - If you need to use mingw git, windows git or some other instead of WSL (if installed), add `alias git=[your git]` in ~/.bashrc
