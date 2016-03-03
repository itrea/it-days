# Welcome to the it-days github.com beginner course

Open up the terminal
```
cd ~/Desktop
or if you have a danish installation
cd ~/Skrivebord
```

To clone this repository open up your terminal/cmd and enter
```
git clone https://github.com/itrea/it-days.git
```

### Tips of the Trade

*How do I ignore files?*
Create a file called `.gitignore` inside your repository

.gitignore
```
.DS_Store # ignore this anoying file on mac
folder\subfolder\* # ignore all files inside a subfolder of a folder
somefolder\*.html # only ignore HTML files inside some folder
```

Dont want to enter your username and password with each push to the remote?
[You should generate an ssh-key and connect it to your github account](https://help.github.com/articles/generating-an-ssh-key/#platform-mac)
# Getting an error when trying to push/pull?
[Try updating the remote origin of your repository](http://stackoverflow.com/a/6565661)
