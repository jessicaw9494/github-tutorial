# GitHub Tutorial

_by Jessica Wu_

---
## Git vs. GitHub
* _**Git**_ is used for version control which takes a snapshot of someones code. 
This is helpful for someone who makes mistakes in the future. 
Futhermore, Git does not require Github. 
In contrast, _**Github**_ does require Git. Github is more specific than Git because it takes 
down every change made and who contributed to that change. 

---
## Initial Setup
_**Initial Setup**_ is used to put a title on any work changed by a person. It is a very convenient
way of saving your project without continual logging in.  

* Set up your Github account:
    1. To begin your Git&Github journey, you would need to create a Github account at [github.com](github.com). 
    This is where you can view and share your codes as a repository (folder).  
    2. Next, make an account on [c9.io](c9.io) and sign in with your Github account. This website is useful 
    for writing and saving all of your code while performing Git and Github. 
* Know your _**SSH Keys**_:
    * SSH (Secure SHell) is a URL or the location of your remote repo. Although _**HTTPS**_ is also a functional URL, HTTPS requires
     you to repeatedly log in every time. However, SSH is more convenient because it only requires 
     you to log in once.  
    * To locate your SSH URL, it can be found in your Github account. This URL is used to clone to your 
    code into c9.
* What is _**git config**_?:
    * `git config` is a command to save your user.name and user.email. Thus, the site can remember you were the 
     one who committed the changes. 
    * The code to do so is `_$ git config --global user.name "your-name"`_ and then 
     `_$ git config --global user.email your-email@site.com"_` 

---
## Repository Setup
A _**Repository Setup**_ is a file that contains your code in Github. You can make as many repos as you want
in a workspace. 

* What is _**git init**_?
    * `git init` is a command to create a new Git repository. It is only mandatory to use this command once.
* How do you _**add**_ and _**commit**_?
    * Add and commit is and important step to do before you push your code to your repository to view on 
    * Github. But you must remember to `cd` into your folder first. 
   1. To add a remote repo, you do `git add "repo-name"`
   2. Next, to commit, you want to do `git commit -m ""message""`
* How to make a new repo on Github?
   1. To make a new repo on Github, all you have to do is press the '+' button right next to your profile icon 
   on Github. 
   2. From there, press 'New Repository', put in your repo name, and press "Create new repository".
* What is a _**remote**_?
    * A remote is a setup to connect your current repository to an external one that lives in Github.

---
## Workflow & Commands
* What are the common workflows and commands you will need to know when using Git&Github?

---