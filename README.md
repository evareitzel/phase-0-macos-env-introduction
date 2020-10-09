# macOS Environment Setup

In this module, we will walk through the process of setting up your macOS local development environment.

## Brief history

### Understanding environments

A **software environment** describes the set of tools that work together to enable you to develop and execute the code that you write. Environments typically include the operating system, databases, programming languages, and related tools like text editors or browsers.

### Comparing environments with machines

You may hear us use the term "software environment" and "machine" to mean similar things. A **machine** describes the physical hardware that your software environment runs on. You'll hear the term machine and computer used interchangeably. Different machines (like PCs and Macs) use different hardware to run the programs that they use. Differences in those machines mean that setting up your development environmnent on one type of machine could look much different than setting it up on another.

### macOS Operating System

In order to work around some of the differences between machines, and specifically between operating systems, we recommend that all students whose computers come pre-installed with the Windows operating system use a tool called **Windows Subsystem for Linux (WSL)**. Windows Subsystem for Linux provides a Linux-based environment for interfacing with and developing on a Windows operating system.

**macOS** is a UNIX-based operating system. UNIX-based operating systems are very commonly used in professional software engineering settings. Learning how to use a UNIX-based operating system will be a valuable skill for your future software engineering career. You may have heard of other UNIX-based operating systems like Ubuntu, Debian, or Fedora, which share a which include the Linux kernel (core software). These types of operating systems work simiilarly.

### Terminals and shells

You may be familiar with opening files and applications on your computer by clicking icons, or viewing a website by typing an address into the address bar and seeing what pops up. These **graphical user interfaces (GUIs)** created a revolution in computing and are still extremely helpful in getting work done for many non-technical computer users.

Before graphical user interfaces (GUIs), the way to tell the computer to do something was through a **terminal**. The terminal included a screen, which would display only text, and a keyboard. The screen and keyboard were connected to a computer and you type into the keyboard what you wanted the computer to do. Then, you press `<Enter>` and would wait for the computer to finish.

Terminals are still used frequently today, especially in software development. We can connect to another computer on the internet, give it instructions by typing in commands, and view the result on our screen. The way that modern computers emulate the terminals of yesterday is through a program called a **command-line interface**, or a **shell**.

Similar to operating systems, there are many different types of shells. The shell that Flatiron School supports on the macOS operating system is called **zsh**, short for Z Shell.

### macOS Terminal

The “Terminal” application is a text-based way to browse and work with files on your computer. We will be using the “Terminal” application during the environment setup and the duration of the program. For now, let's start to see what "Terminal" and more generally, **shell**s can do.

## Action items: view your desktop in "Finder" and "Terminal" applications

In order to complete the environment setup, you will need to be able to open applications. You can open new applications by using the search bar at the bottom of your screen. The search bar says “Type here to search”.

### View your desktop in the "Finder"

The "Finder" application is a visual way to browse the files on your computer. You may already be familiar with the "Finder" application. This application allows you to quickly see the files on your desktop, downloads, documents, pictures, music, videos, and much more.

1. Click on the "Spotlight Search" magnifying glass icon in the top-right corner of your window
2. Type "Finder" and open the application
3. Find and open the “Desktop” folder in your "Finder" application

### View your desktop in the "Command Prompt" shell

The "Terminal" application is the terminal that will allow us to interface with our computer through a shell. This action item is to primarily get you comfortable running commands in _any_ shell so that you can work through the environment setup on your own.

1. Open the "Terminal" application using the "Spotlight Search"
2. Type `cd /Users` into the terminal and press `<Enter>`
3. Type `ls` into the terminal and press `<Enter>`
4. Look for your username in the list
5. Type `cd` into the terminal, add a space, and type your name as it appears in the list and press `<Enter>`
6. Type `ls` into the terminal and press `<Enter>`
7. Look for the “Desktop” folder in the list
8. Type `cd Desktop` into the terminal and press `<Enter>`
9. Type `ls` into the terminal and press `<Enter>` (Note: if prompted, allow "Terminal" to access files in your Desktop folder.)

### Check your work

If you were able to open your desktop in the "Finder" application and you were able to open the "Terminal" application and `cd` to your desktop in that application, you should see that you can see the same list of files in both the **graphical user interface (GUI)** and in the **command-line interface (CLI)** or shell.

This may be your first time using the "Terminal" application or any terminal or shell. Now you know how to see the items on your desktop through the "Finder" application _and_ through the "Terminal" application.

## Preparing for your environment setup

Using multiple windows, downloading and installing programs, terminology and symbols we'll use, starting and stopping, reaching out for help