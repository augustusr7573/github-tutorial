# GitHub Tutorial

_by Augustus Roman_

---
## Git vs. GitHub
Git is the local where the code is at.
Github is a website is where you can upload your code to the cloud keeping it safe if anything bad happens to the code at git you call always pull whatever was saved in the cloud as well and its great.


---
## Initial Setup
##### This is how you make a github account where things form git get send to the cloud(github)
To set up your github account all you would need to do is head to this link here [GitHub](https://github.com/join)
And simply just put in your email username and password.
##### The ide is were all the code goes this is git and were its used.
Follow the instructions above and when you set that up you should head to this link [ide](Ide.cs50.io) and sign in with your username and passwords you just made moments ago.

---
## Repository Setup
* In order to set up a repository go to github and login then hit the plus sign in the right hand corner then click on new repository give it a name then you click create repository at the bottem you add a description but thats up to you.  
* You also want to be on ssh all the time if you are cloning or connecting the the remote or repository.
Now in order to connect your self to the remote to the cloud
Type git init in the beginning to really start you will know this worked if it says master somerwhere in the beginning of the line
#### touch file(what ever you want the name to be)
To add file you for you to type things in.
#### c9 file 
The file name you just typed in ; in order to go itto you type touch so that way we can get started.
#### git add .
So when you add all the code you wanted then you have to save it using  
#### git commit -m "message"
Then you have to use this command to make it as a definit save of your work.  
When you put a message make it simmilar to something you changed or did 

---
## Workflow & Commands
So 2 more commands for you to know is... 
#### git status
What git status does is that it will let you know if you have added the code to the stage and if you have commited your last changes.  
#### git push
If you have connected your repo to the code then you type this in and all the code will be pushed onto github but make sure you have added and commited. 

---
## Rolling Back Changes
_Where it says file just put the files name like for me it is README.md_  
#### git checkout -- file
To discard changes that werent added or commited all you have to do is type this in.
#### git reset HEAD file
To undo something you had added to the stage you just type that in.
#### git reset --soft HEAD~1, & git reset --hard HEAD~1,
Both do the same thing exept hard mean it deletes everything completely like the save and the latest code ; and soft means it will rmove only the screenshot. 
#### git log
Look for the previous commit before you had changed it then you will type 
#### git revert 
Then you will copy the sha ten paste right after revert then you will type in git reset --hard HEAD~1 in order to stop then push it again to git hub.