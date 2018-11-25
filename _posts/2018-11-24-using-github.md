---
layout: post
title: Using Github!
subtitle: Learn to use for your projects.
---

This post is all about Using Github for your project.

Git as we all know is a version controlling system. It keeps a track of your changes and saves it in cloud in github.com or your enterprise domain if using any company/corporate account. This post is to drive you through the usage of most common git commands and their common usage in day to day life.

&nbsp;

## Installations

#### MacOS
* Install Homebrew from [https://brew.sh/](https://brew.sh/). Then follow the command to install git in MacOS.

        brew install git

&nbsp;
#### Windows
* Install git from [Git](https://gitforwindows.org/) for Windows.

&nbsp;
#### Linux
- To know if your system is Debian or Red Hat Based System. You can follow this stackexchange [url](https://unix.stackexchange.com/questions/29981/how-can-i-tell-whether-a-build-is-debian-based).

&nbsp;

##### Debian Based
Follow the commands to install git in your Debian System.
            
    sudo apt-get update
    sudo apt-get upgrade
    sudo apt-install git


##### Red Hat Based
Follow the commands to install git in your Red Hat Based System.

    sudo yum upgrade
    sudo yum install git

&nbsp;

## Configurations
The very first thing to do when using git is to setup your email id and name. To do so, follow the below command.

    git config --global user.name "John Doe"
    git config --global user.email johndoe@example.com

You can check these settings ```git config user.name``` or you can check all the config settings and their respective values using ```git config --list```.

#### Setting Up SSH Keys
Since github needs to know your identity before any changes goes to github remote repo. Therefore, we have to provide our credentials (username and password) before pushing any changes to remote (this is the version of something that is hosted on a server, most likely GitHub). The alternate way to authenticate yourself is to use ssh key added to your github account. Github's official documentation is the best place to setup for SSH keys.
[Github's Official Documentation for SSH Keys](https://help.github.com/articles/connecting-to-github-with-ssh/)