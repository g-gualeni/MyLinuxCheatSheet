# MyLinuxCheatSheet
My personal collection of Linux commands

`sudo apt update`: update current installation

`sudo apt upgrade`: upgrade (move to new software version)

# Qt Installation
`sudo apt-get install build-essential libgl1-mesa-dev`

this is the command line to install all necessary packages

To be able to modify a widget, you need to force QtCreator to use Wayland. So open the folder

`/home/<username>/Qt/Tools/QtCreator/bin`

in the terminal, then run this command:  
`$ export QT_QPA_PLATFORM=wayland`

then run QtCreator using:
`./qtcreator`
  
Get the info from here:  
https://forum.qt.io/topic/144831/recent-upgrade-to-ubuntu-23-04-breaks-qt-designer/6

If you get an error like this:
![image](https://github.com/g-gualeni/MyLinuxCheatSheet/assets/2716458/961da1d4-635d-47a9-8aa7-8b31c41f873b)

https://stackoverflow.com/questions/77725761/from-6-5-0-xcb-cursor0-or-libxcb-cursor0-is-needed-to-load-the-qt-xcb-platform 
then use:

`sudo apt-get install libxcb-cursor0`

# Git
`gh repo clone`: this is the command for GitHub CLI interface to clone a project. 
The command can be copied from GitHub Repository page

`git status`: this is the command that can tell you if there are some modifications in the folder

`git add .`: don't forget this command or new files will not be in the new commit

`git commit -m"My Commit message" -a`: This is the add and commit command

`git push`: once done, push the modifications to the server


`git fetch`: scarico tutti gli aggiornamenti dal server

`git pull`: prendo dal server gli aggiornamenti del ramo corrente e passo all'ultimo commit

`git banch -a`: list all ovvero vedo tutti i branches, anche quelli remoti, e posso vedere anche i corrispondenti rami locali

`git switch -c <localbranch> <origin/RemoteBranch>`: this is the command to switch and checkout a remote branch 

`git log`: serve per vedere tutti i messaggi di commit in ordine cronologico inverso

`git checkout <branch>`: passo al branch selezionato 

`git push -u origin <branch>`: Se voglio fare un push di un branch che esiste solo localmente, non sul server


# Ubuntu nuts
Right click sucks! Try to do it 2 times and fast











