# github.com beginner course
Welcome to our Github it-days course

If you haven't already setup your username and email do this in your Terminal/CMD
```
git config --global user.email "enter your email here"
git config --global user.name "enter your name here"
```

Open up the terminal/CMD
```
# Mac/Linux:
cd ~/Desktop

# Windows
cd C:\Users\*your username*\Desktop
```

To clone this repository open up your terminal/cmd and enter
```
git clone https://github.com/itrea/it-days.git
```

# Tips of the Trade

######How do I ignore files?

Create a file called `.gitignore` inside your repository

_.gitignore_
```
.DS_Store # ignore this anoying file on mac
folder\subfolder\* # ignore all files inside a subfolder of a folder
somefolder\*.html # only ignore HTML files inside some folder
```

######Dont want to enter your username and password with each push to the remote?
[You should generate an ssh-key and connect it to your github account](https://help.github.com/articles/generating-an-ssh-key/#platform-mac)

######Getting an error when trying to push/pull?
[Try updating the remote origin of your repository](http://stackoverflow.com/a/6565661)
