# Operating System Project Documentation

## a. Zorin OS Installation

This documentation explains how to install Zorin OS using VirtualBox.  
First, the Zorin OS ISO file is downloaded from the official website.  
A virtual machine is created in VirtualBox with adjusted RAM and storage settings.  
The ISO is booted, and the guided installer is followed to complete the OS setup.  
This process provides a Linux-based environment for system-level development.

## b. System Call (Implementation)
 
System calls are interfaces between user programs and the operating system kernel.  
This project uses the `uname()` system call to retrieve system information such as OS name, version, and architecture.  
The `uname()` call fills the `utsname` structure with these details.  
A simple C program was written to display the output of this system call.  
It shows how a user-level program can request system-level information through the Linux kernel.
