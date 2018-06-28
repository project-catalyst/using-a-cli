# Using a Command Line Interface

Note: This document is a work in progress. If you find yourself here and have suggestions for how to improve it or questions contact me on twitter [@dwesty17](https://twitter.com/dwesty17) or by email at j.dylan.westerhold@gmail.com. I'll do my best to get back to you.

Reading Time: **? minutes**

## Lessons
1. **Using a Command Line Interface**
1. [Installing Homebrew](https://github.com/project-catalyst/installing-homebrew) (? minutes)
1. [Running JavaScript Programs](https://github.com/project-catalyst/running-js-programs) (? minutes)
1. [Using Git and GitHub](https://github.com/project-catalyst/using-git-and-github) (? minutes)
1. [Intro to JavaScript](https://github.com/project-catalyst/overview) (? minutes)
1. [JavaScript Lesson 1: Variables and Data Types](https://github.com/project-catalyst/overview) (? minutes)
1. [JavaScript Lesson 2: Functions](https://github.com/project-catalyst/overview) (? minutes)
1. [JavaScript Lesson 3: Conditional Statements and Loops](https://github.com/project-catalyst/overview) (? minutes)
1. [Intro to React](https://github.com/project-catalyst/overview) (? minutes)

## Overview

A command line interface (CLI) is an alternative way than what you're probably used to of interacting with your computers operating system and some software you've installed. Normally you interact with your computer by using its graphical user interface (GUI), which is a more modern invention than the CLI.

A CLI is used by typing a series of commands for your machine to execute. You can use a CLI without a mouse. By contrast a GUI is visiually driven with things like icons and menus that you can click on. A CLI typically has a steeper learning curve than a GUI, which is built to be very user friendly.

Developers use CLIs for a lot of things like running their code and unit tests or pushing their code to a remote repository and much more.

## How to Guide

For this section I'll assume that you're using the default Terminal application running bash as it's shell. You can see some [alternative](#Alternatives) setups below. I'd recommend trying `iTerm2` and `fish` (or any other combination that seems interesting) once you feel comfortable on the command line. 

You can open the Terminal application through Mac's Spotlight feature by typing "Terminal" and selecting the top hit. Each terminal window is associated with a directory in your computer's file system. In the next section and following lessons you'll learn the first few commands to run.

## First Commands to Learn

### pwd

_present working directory_: prints out the directory that this terminal window is. currently associated with

```shell
> pwd
/Users/dylanwesterhold/developer/project-catalyst
```

### ls

_list_: lists all the directories and and files in the present working directory.

```shell
> ls
overview    using-a-cli
```

### cd

_change directory_: changes to the directory specificed by the relative path listed after the command. In the absence of a path `cd` changes to the users root directory.

```shell
> cd
> pwd
/Users/dylanwesterhold
```

```shell
> cd developer/project-catalyst/
> pwd
/Users/dylanwesterhold/developer/project-catalyst
```

```shell
> cd using-a-cli/
> pwd
/Users/dylanwesterhold/developer/project-catalyst/using-a-cli
```

### brew

[Installing Homebrew](https://github.com/project-catalyst/installing-homebrew)

### node

See [Running a Javascript Program](https://github.com/project-catalyst/running-a-javascript-program)

### git

See [Using Git and Github](https://github.com/project-catalyst/using-git-and-github)

## Tips (optional)

`man` is a command that can come in handy when you aren't sure about how something works. Typing `man <some other command>` will print the documentation for that command to your terminal. To escape the documentation you can type `:wq` and hit enter.

## Alternatives (optional)

Neither of the following lists are all encompassing. Mac's come with solid defualt terminal application and shell, but there are alternatives.

### Terminal Applications

The actual application you open on your computer.

* Terminal: Default terminal application that comes preinstalled on Macs 
* [iTerm2](https://www.iterm2.com/): Alternative terminal application that can be intstalled with some more advanced features

### Shells

The interpreter that parses and processes your commands.

* [bash](https://www.gnu.org/software/bash/)
* [fish](https://fishshell.com/)
* [zsh](http://ohmyz.sh/)

## Next Lesson

[Installing Homebrew](https://github.com/project-catalyst/installing-homebrew)