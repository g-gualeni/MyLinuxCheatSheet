# MyLinuxCheatSheet
My personal collection of Linux commands

`sudo apt update`: update current installation

`sudo apt upgrade`: upgrade (move to new software version)

# Qt Installation
`sudo apt-get install build-essential libgl1-mesa-dev`: this is the command line to install all necessary packages

https://forum.qt.io/topic/144831/recent-upgrade-to-ubuntu-23-04-breaks-qt-designer/6
Rrm.majd 10 giorni fa
@JonB

Adding "export QT_QPA_PLATFORM=wayland" to my .profile fixed the problem and everything is fine now.

this worked for me, i can now drag and drop in the editor without issues. thanks.


# Git
`gh repo clone`: this is the command for GitHub CLI interface to clone a project

`git status`: this is the command that can tell you if there are some modifications in the folder

`git add .`: don't forget this command or new files will not be in the new commit

`git commit -m"My Commit message" -a`: This is the add and commit command

`git push`: once done, push the modifications to the server





