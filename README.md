# Team-Rio
Repository For Team Rio

> # VERSION CONTROL 

# VERSION CONTROL WITH GIT AND GITHUB :gear:


<p> Before we start, we recommend to use  vscode and the linux OS i.e any distribution for best developer experience. this doesnt mean windows or macOs won't work all the commands are universally compatible. 
</p> 

> ## This illustration is done on the ubuntu terminal. 

> When creating new project on the local machine.
*  launch terminal ``` ctrl + Alt + T ```
*  move to the project directory ie. Desktop/Project  ```cd Desktop/Project ```
*  or create a new project directory ```mkdir Project```
*  then change into the project directory ```cd Project```

*  initialise our folder to a git repository ```git init```
*  create a file using vscode ```<new>``` 
*  for those who wouldn't wish to leave terminal yet you could use "pico" ```pico <new>```
*  add some content into the file for this case we would be using ```Hello Team Rio```
*  we could at this point want to check the working tree ```git status```
*  add a file to the working tree. ```git add -A```
*  committ the change to our repository. ```git commit -m <new>```
*  check the status. ```git status```
*  create branches. ```git checkout -b <new branch name>```
*  change into a different branch.  ```git branch <branch name>```

> When cloning a git repository onto your local machine. ```(HTTPS option)```
*  launch terminal ``` ctrl + Alt + T ```
*  move to the project directory ie. Desktop/Project  ```cd Desktop/Project ```
*  or create a new project directory ```mkdir Project```
*  then change into the project directory ```cd Project```
* identify the repository you would wish to clone from github
<p float="left">
<img src="screenshots/clone-1.jpg" width="200px" />
</p>

* copy the url link to your terminal window ```git clone https://github.com/SpaceyaTech/Team-Rio.git```
* identify files to change and start editing.
* run git status to check on the working tree ```git status```
* before we make any commits we should change to our own branch since this is a group project. ```git checkout -b <new branch name>```
*  change into a different branch.  ```git branch <new branch name>```
* add your edits to the working tree by running ```git add <filename(s)>```
* committ the change to our repository. ```git commit -m <new>```
## <p> after we have commited the changes we have to push our code to github we could run a number of commands for this: </p>
* ```git remote```
* ```git fetch```
* ```git push```
* ```git pull```

> for this case we will only use ```remote``` and ```push```
* we first set the remote link ```git remote add <name> <url>``` 
* then push using ```git push <remote> <branch>```
## <p>for the team-rio repository we do the following:</p>
* we add the remote link ```git remote add origin https://github.com/SpaceyaTech/Team-Rio.git```
* then we push our code ```git push -u origin <branch name>```

> When cloning a git repository onto your local machine. ```(SSH option)```

> ## This is open to edits and more contribution.

> ## An illustration on VSCode is also welcome.