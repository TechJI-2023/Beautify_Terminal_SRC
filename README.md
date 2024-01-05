# Beautify_Terminal

## Introduction

- What is terminal?
  - A terminal is a text input and output environment. It is a program that allows users to enter commands that the computer processes.

- The difference between terminal and terminal emulator
  - Terminal emulator emulates a terminal. It is a software program replicates the functionality of a terminal within a GUI environment.

## Recommend TTY

- Windows
  - Windows Terminal
    - Modern, fast, efficient, powerful, and productive terminal application for users of command-line tools and shells.
  - FireCMD
    - User-friendly and powerful command line environment
    - Allows running multiple console applications simultaneously
    - Includes a text editor for editing text files
    - Supports command auto-completion
  - MobaXterm
    - Versatile with support for many protocols
    - Integrated X server for X11 forwarding
    - Session management and multi-execution
    - Includes graphical SFTP browser and text editor
    - With many useful tools

- macOS
  - kitty
    - cross-platform
    - open-source
    - extensive customization, including changing the font, colors, and keyboard shortcuts
    - multiple windows and tabs
    - offloads rendering to the GPU for lower system load and buttery smooth scrolling
  - Alacritty
    - Easy to use, depend on OpenGL, support Chinese
    - Rust, safer to deal with memmory
  - ZOC
    - support various terminal types, like xterm and vt220
    - modern user interface
    - easy to manage and organize sessions and folders

- Linux
  - Terminator
    - Support multiple sessions and tabs
    - Highly customize
    - Open-source and cross-platform
    - Allows typing on multiple grouped terminals simultaneously
  - Guake Terminal
    - Multi-monitor support
    - Change apperance
    - Ability to split tabs horizontally and vertically
    - Change the default shell from abailable options

- Commonly used operations:(may vary depending on the terminal emulator)

  - **Switching Between TTYs**: You can switch between different TTYs by using the `Ctrl+Alt+F#` key combination, where `#` is the number of the TTY you want to switch to.

  - **Clearing the Screen**: You can clear the screen by using the `clear` command.

  - **Scrolling**: You can scroll through the output using `Shift+Page Up` and `Shift+Page Down`.

  - **Terminating a Process**: You can terminate the currently running process by using the `Ctrl+C` key combination.

  - **Suspending a Process**: You can suspend the currently running process by using the `Ctrl+Z` key combination.

  - **Searching Through History**: You can search through your command history by using the `Ctrl+R` key combination and then typing the command you're looking for.

  - **Auto-Completing Commands**: You can auto-complete commands by typing the first few letters and then pressing the `Tab` key.

  - **Changing Text Appearance**: You can change the appearance of the text in the terminal using various ANSI escape codes. For example, `echo -e "\e[31mHello World"` will print "Hello World" in red.

  - **Redirecting Output**: You can redirect the output of a command to a file using the `>` operator. For example, `ls > file.txt` will save the output of the `ls` command to `file.txt`.

  - **Piping Output**: You can pipe the output of one command to another using the `|` operator. For example, `ls | grep txt` will search for files with "txt" in their name.

## Introduction to some pluggins for powershell and zsh

- zsh [link](http://zsh.sourceforge.net)
  - oh my zsh [link](https://ohmyz.sh)
    -Oh My Zsh is a delightful, open source, community-driven framework for managing your Zsh configuration. It comes bundled with thousands of helpful functions, helpers, plugins, themes, and a few things that make you shout... "Oh My ZSH!"
  - antigen [link](https://github.com/zsh-users/antigen)
    - Antigen is a small set of functions that help you easily manage your shell (Zsh) plugins, called bundles. The concept is pretty much the same as bundles in a typical vim+pathogen setup. Antigen is to Zsh, what Vundle is to vim.
  - zplug [link](https://github.com/zplug/zplug)
    - Zplug is a next-generation Zsh plugin manager.
  - zgen [link](https://github.com/tarjoilija/zgen)
    - Zgen is a lightweight and fast plugin manager for Zsh.

- windows
  - oh my posh [link](https://github.com/JanDeDobbeleer/oh-my-posh)
    - Oh My Posh is a prompt theme engine for any shell.

- Package managers for none Linux users
  - macOS
    - homebrew [link](https://brew.sh)
      - Homebrew is a free and open-source software package management system that simplifies the installation of software on Apple's macOS operating system and Linux.
    - macports [link](https://www.macports.org)
      - The MacPorts Project is an open-source community initiative to design an easy-to-use system for compiling, installing, and upgrading either command-line, X11 or Aqua based open-source software on the macOS operating system.
  - windows
    - winget [link](https://github.com/microsoft/winget-cli)
      - Windows Package Manager (aka winget) is a free and open-source package manager designed for Microsoft Windows 10. It consists of a command-line utility and a set of services for installing applications.
    - scoop [link](https://scoop.sh)
      - Scoop is a command-line installer for Windows inspired by Homebrew.
    - chocolatey
      - Chocolatey is a machine-level, command-line package manager and installer for Windows software. It uses the NuGet packaging infrastructure and Windows PowerShell to simplify the process of downloading and installing software.