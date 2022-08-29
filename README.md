# **CLONING WITH VIRTUAL MACHINE**

**THIS DOCUMENT EXEMPLIFIES THE USE OF VIRTUALBOX (A VIRTUAL MACHINE) TO CLONE A REMOTE REPOSITORY TO AN INITIALIZED LOCAL REPISITORY**

*steps taken to do these are:*

1).create a directory and initialize git.
   `mkdir directory; cd directory && git init`

2.). create project files you had like to commit e.g project.txt, README.md etc.

3.). Add these files and commit them.
    `git add . && git commit -m 'my first commit' `

4). Insert your github credentials to identify yourself. <br>
     `git config --global user.name "github username" <br>
     `git config --global user.email "your github email"

5). add or connect to a remote branch (which is the one created using github graphical interface). <br>
   `git remote add origin https://github.com/your@githubemail/directory.git` <br>
   or by using ssh url <br>
   `git remote add origin git@github.com:github_username/directory.git`

6). push local repo to remote origin
    `git push origin main/master`

**DONE! THAT'S IT**
