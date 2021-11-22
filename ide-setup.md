# Setting up your IDE

In order to develop software in VCE Software Development, you will need to set up the required tools: Git, Python, and Visual Studio Code.

Contents:

1. [What is an IDE?](#what-is-an-ide)
2. [Steps](#steps)

## What is an IDE?

The most important tool for the software developer is their _Integrated Development Environment_ (IDE). Technically, an IDE is not just one tool but a collection of tools that help programmers write code. Typicaly, an IDE provides:

* Code editing with syntax highlighting and autocompletion
* debugging tools
* version control
* support for multiple languages
* and more!

Programmers should choose and customise an IDE to meet their specific needs. This guide will set you up with an IDE that will work well for VCE Software Development (and is commonly used by professional software developers around the world! 💻🌏). _Don't worry if you're not sure what all of these things are just yet, we will cover them in more detail during the course_.

## Steps

### Install required software

Download and install the following software:

1. [Git](https://git-scm.com/)
1. [Python](https://www.python.org/downloads/) (❗️☑️ 'add Python to PATH')
1. [Visual Studio Code](https://code.visualstudio.com/)

### Perform setup for Git

1. Start VSCode (ignore the 'start' screen for now)
1. Open a terminal using <kbd>Ctrl</kbd><kbd>\`</kbd> (Windows/Linux) or <kbd>⌘</kbd><kbd>\`</kbd> (macOS)
1. If you are connected to the school network, type the following command (and press <kbd>⏎</kbd>):

    `git config --global http.proxy http://10.179.176.19:8080`

    _If you connect to a non-school network later, you will need to run the following command:_

    `git config --global --unset http.proxy`

1. Perform your user setup for `git` with the following commands (using your own name and school email)

    `git config --global user.name "Firstname Lastname"`

    `git config --global user.email las0001@millparksc.vic.edu.au`

### Configure VSCode to support Python

1. Open the extensions sidebar in VSCode with <kbd>⇧</kbd><kbd>Ctrl</kbd><kbd>X</kbd> (Windows/Linux) or <kbd>⇧</kbd><kbd>⌘</kbd><kbd>X</kbd> (macOS)
1. Search for 'Python' and install the extension by Microsoft
1. Open the command palette with <kbd>⇧</kbd><kbd>Ctrl</kbd><kbd>P</kbd> (Windows/Linux) or <kbd>⇧</kbd><kbd>⌘</kbd><kbd>P</kbd> (macOS)
1. Search for 'Python', and select 'Python: Select Interpreter'
1. Select the latest version of Python available

### Congratulations! 🎉

You are now ready to start your [first assignment](helloworld.md)!
