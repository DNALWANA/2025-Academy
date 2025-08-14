# Cloning
Alright! setting up git and github is not hard at all right, okay now lets get you going to the first thing in git here, **git clone**.

What is `git clone` ?

This command is basically a command that will let you "clone" a git based repository from a git server.

git server ??? yes if youre wondering, github is one of git server, git server is basically a server that store git based repository so that people can access those repositories remotely (not in their own pc).

[==] Okay lets just use this directly so you understand it way better, first lets create a new repository in your github account, go this url to do this https://github.com/new.

[==] Fill in the repository name with whatever name you would want the repository be, for this course, lets say, "learn_github_course" (make sure you dont put spaces in the name, or else it would be replaced with `-`).

[==] Public repository means that other people will be able to see your repository as well, if you dont want that, then you can set it to private, but lets set it to public first for this time.

[==] And click the "create repository" button on the very bottom of the screen.

Congratulations you have just created your (probably) first ever repository in github!!!

[==] Now next, you can go to your terminal if you are in Linux/MacOS, or open up the git bash if you are in Windows, and then you can `cd` (change directory) to a place where you want to put the repository in.

[==] Copy and run these commands down below, make sure you change everything inside a curly bracket:
```
mkdir {your repository name}
cd {your repository name}
git init
echo "Hello World" >> README.md
git add .
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/{your github account username}/{your repository name}.git
git push -u origin main
cd ..
```
And then you remove that folder.

Dont worry if you dont understand those commands yet, you will eventually understand it in the end of this course.

[==] And then back to the github repository, you can click on the "Code" button with the green color on it, choose "https" copy the url there, and then back to the terminal/git bash and type `git clone {the url that you have just copied}`, ex: `https://github.com/Daskom-Lab/2024-Academy.git` (make sure you clone your repository, not the d1337lands one)

Boom! now you get it right ?
