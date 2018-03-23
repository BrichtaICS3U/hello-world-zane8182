learnGitPython
by JP Brichta
March 2018

This repository contains a simple Python code for "Hello world". Students are required to:

1. Clone the repository to their computer.
2. Change the file so that it says, "Hello <student's name>".
3. Commit changes to the repository.
4. Push the changes to their repository.

Some commands that might be helpful:

Git Bash Commands (Basic)

For navigating around the file system:

mkdir <folder>        Make a new folder called <folder> in the current folder. (Don’t include the <> symbols)
ls                    List the files and folders in the current folder
cd <folder>           Change directory to <folder>. (Don’t include the <> symbols.) The folder must already exist.

Examples:
cd python
cd d:\python\finalProject
cd ..                 Change directory by closing the present folder and move up one “level” in the folder tree.

For using Git: 
git clone <link>        Clone a repository from GitHub. Use the mouse to copy and paste the <link>. Once again, don’t include                         the <> symbols
git status              Show the status of the current repository. Any newly created files will show up in red. Any newly                             added files will show up in green
git add .               Add any newly created file to the local repository
git commit -m “<message>”   Commit changes to the local repository with a message. You must always include a message
git push                Push the changes in the local repository to the remote repository on Github.com
git pull                Check that the local repository is up to date with the remote repository.
