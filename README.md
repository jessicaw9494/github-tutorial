# GitHub Tutorial

_by Jessica Wu_

---
## Git vs. GitHub
 _**Git**_ is used for version control which takes a snapshot of someones code. 
This is helpful for someone who makes mistakes in the future. 
Futhermore, Git does not require Github. 

In contrast, _**Github**_ does require Git. Github is more specific than Git because it takes 
down every change made and who contributed to that change. 

---
## Initial Setup
_**Initial Setup**_ is used to put a title on any work changed by a person. It is a very convenient
way of saving your project without continual log in.  

* Set up your Github account:
    1. To begin your Git&Github journey, you would need to create a Github account at [github.com](github.com). 
    This is where you can view and share your codes as a repository (folder).  
    2. Next, make an account on [c9.io](c9.io) and sign in with your Github account. This website is useful 
    for writing and saving all of your code while performing Git and Github. 
* Know your _**SSH Keys**_:
    * SSH (Secure SHell) is a URL or the location of your remote repo. Although _**HTTPS**_ is also a functional URL, HTTPS requires
     you to repeatedly log in. However, SSH is more convenient because it only requires 
     you to log in once.  
    * To locate your SSH URL, it can be found in your Github account. This URL is used to clone into c9.
* What is _**git config**_?:
    * `git config` is a command to save your user.name and user.email. Thus, the site can remember you were the 
     one who committed the changes. 
    * The code to do so is `$ git config --global user.name "your-name"` and then 
     `$ git config --global user.email your-email@site.com"` 

---
## Repository Setup
A _**Repository Setup**_ is a file that contains your code in Github. You can make as many repos as you want
in a workspace. 

* What is _**git init**_?
    * `git init` is a command to create a new Git repository. It is only mandatory to use this command once.
* How do you _**add**_ and _**commit**_?
    * Add and commit is and important step to do before you push your code to your repository to view on 
    Github. But you must remember to `cd` into your folder first. 
   1. To add a remote repo, you do `git add repo-name`
   2. Next, to commit, you want to do `git commit -m "message"`
* How to make a new repo on Github?
   1. To make a new repo on Github, all you have to do is press the '+' button right next to your profile icon 
   on Github. 
   2. From there, press 'New Repository', put in your repo name, and press "Create new repository".
* What is a _**remote**_?
    * A remote is a setup to connect your current repository to an external one that lives in Github.

---
## Workflow & Commands
* What are the common workflows and commands you will need to know when using Git&Github?
    * `git status`: This command is to make sure everything you are typing has no errors and will inform you 
    when you do. It is recommended to use this command often.
    * `git add `: This command will let you add a remote repository.
    * `git commit -m ""`: This command will allow you to write a message as a reminder of what change you had made.
    * `git push`: This command will push your changes to Github in order to be viewed by the public and/or shared
    to the public.

---
## Collaboration
Have you ever wanted to collaborate on a project with someone, fix an error that they made, or simply improve their 
code? Well you can with Git&Github!

* _**Fork and Clone!**_: Forking and Cloning is an easy way to bring someone else's repository to you and then you 
can make the changes.
    * To Fork, all you need to do is press the _'Fork'_ button on the other person's repository page and you know when
    it's complete when you see `forked from username/repositoryname` under your username.
    * To Clone, go to your c9 account and type in 'git clone' with the SSH URL that can found in the right hand side
    of your repository page on Github. 
* Just because you have saved and copied one's project does not mean your done! You must share and be accepted by the
other user! That's why we have _**Pull Requests**_.
    * To make your pull request, you must press the green squared button on your Github repo page and then press 
    _'Create pull request'_.
    * From there, the other person can view your edits/changes before they accept your changes.

---
## Error Handling

When you come across an error, no fret! 

* If you ever `init` in the wrong directory, you can `cd` your way out and then remove your repository by using the
command `rm -rf dir-name`.