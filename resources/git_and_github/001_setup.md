# Setup

The very first thing that you have to do is to create an account in github.com if you haven't done that by simply going to [here](https://github.com/signup).

After you have an account on github, now lets go to the next step, install the git cli application, and remember we will always use CLI (Command Line Interface) from now on, so make yourself comfortable in using it!

**Installing git cli is different for two major OS:**

- For Windows, you would want to go to https://git-scm.com/download/win and then download the binary (Git.blablabla.exe), and then start the installation wizard, make sure you read carefully the options there, but because you are just starting out **dont** change any of the default choices there.

- For Linux, go to terminal and simply type `sudo apt-get install git` and you're done.

- For MacOS, luckily git is already comes preinstalled with your operating system, so be happy with that!

If you still confused of what written in here regarding the git cli installation, you can refer to this gists https://gist.github.com/DCRichards/7c7189787429cee79e866da4bc2c5782 to see some other way.

**configuring git**
After installation, configure your git settings

- set your username: `git config --global user.name "your name"`
- set your email:
  `git config --global user.email "examplemail@example.com"`
- to verify your settings, you can use:
  `git config --list`
