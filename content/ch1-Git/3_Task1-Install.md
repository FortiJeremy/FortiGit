---
title: "Task 1 - Install Git"
chapter: true
weight: 3
---

## Task 2 - Install Git 

To install Git, follow the directions provided by the official website: 
https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

(excerpts taken from above webpage, as of 04-17-2023)

### Installing on macOS

There are several ways to install Git on macOS. The easiest is probably to install the Xcode Command Line Tools. On Mavericks (10.9) or above you can do this simply by trying to run git from the Terminal the very first time.

$ git --version

If you don’t have it installed already, it will prompt you to install it.

If you want a more up to date version, you can also install it via a binary installer. A macOS Git installer is maintained and available for download at the Git website, at https://git-scm.com/download/mac.

### Installing on Windows

There are also a few ways to install Git on Windows. The most official build is available for download on the Git website. Just go to https://git-scm.com/download/win and the download will start automatically. Note that this is a project called Git for Windows, which is separate from Git itself; for more information on it, go to https://gitforwindows.org.

To get an automated installation you can use the Git Chocolatey package. Note that the Chocolatey package is community maintained.

! Its recommended for our workflows to install Windows Subsystem for Linux 2 (WSL2). Example instructions for installing Ubuntu on WSL2 can be found here:
https://ubuntu.com/tutorials/install-ubuntu-on-wsl2-on-windows-11-with-gui-support#1-overview
With WSL 2 installed, you can install via Linux instructions below.

### Installing on Linux

If you want to install the basic Git tools on Linux via a binary installer, you can generally do so through the package management tool that comes with your distribution. If you’re on Fedora (or any closely-related RPM-based distribution, such as RHEL or CentOS), you can use dnf:

$ sudo dnf install git-all

If you’re on a Debian-based distribution, such as Ubuntu, try apt:

$ sudo apt install git-all

For more options, there are instructions for installing on several different Unix distributions on the Git website, at https://git-scm.com/download/linux.


### Post Install

After installing, you can validate your installation by entering **git --version** from the cli:
    jeremy@localhost:~/repos/FortiGit$ git --version    
    git version 2.34.1
