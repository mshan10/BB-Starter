# Project

Personal Website


## Setup
#### Terminal 

**Windows Users**  
Windows uses a DOS based terminal with the command prompt in contrast to a UNIX based system present in Mac Linux devices. UNIX is a much more standard and intuitive command line interface to use so we will need to download a UNIX based command line. Some options are [Ubuntu](https://ubuntu.com/tutorials/ubuntu-on-windows#1-overview) which is installed on Windows Subsystem for Linux or [Git](https://git-scm.com/downloads)

**Mac Users**  
Use default terminal which is Unix based

**Basic Commands**  
`ls` - lists the files in your current directory  
`ls -l` - lists the files in your current directory in detailed view  
`ls -a` - lists the files in your current directory including hidden files  
`cd {foldername}` - change directory to specified path of folder  
`mkdir {foldername}` - create folder at current location with specified file name  
`pwd` - tells you where you currently are  


#### Github 
Create a Github account at [https://github.com/](https://github.com/). 

Configure your user information on local computer
```bash
git config --global user.name "{firstname lastname}"
git config --global user.email "{valid-email}"
```

Clone the project by navigating to the desired folder and running `git clone git@github.com:mshan10/BB-Starter.git`. 


Basic Git commands [here](https://education.github.com/git-cheat-sheet-education.pdf):  
`git status` - shows the modified files  
`git add {file}` - adds a file to your next commit  
`git commit -m "{message}"` - commits your staged content  
`git push` - send committed changes to the remote branch  
`git branch` - check which branch you are on  
`git checkout {branchname}` - switch to new branch  

#### IDE (Integrated Developing Environment)
IDE is basically your code editing environment. You can edit on the command line with vim/nano or on a separate environment like VSCode.  

[vim](https://www.vim.org/) (Recommended)  
[VScode](https://code.visualstudio.com/) (Recommended)  
[Atom](https://atom.io/)  
[SublimeText](https://www.sublimetext.com/)  
[Notepad++](https://notepad-plus-plus.org/downloads/)

## Languages
#### Python Installation

Install the latest version of [Python](https://www.python.org/downloads/). Make sure to check the *Add Python to Path* option.

Test python by running 
```bash
python3 --version
```

#### React
This will be our front end framework. Read more about React [here](https://reactjs.org/).

#### NodeJS/Express
This is one example of a backend framework. Read more about it [here](https://nodejs.org/en/)

## License
[MIT](https://choosealicense.com/licenses/mit/)