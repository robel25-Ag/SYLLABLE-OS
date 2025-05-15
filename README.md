# Syllable OS Documentation

## a. OS Installation (Syllable OS)

Syllable OS is a lightweight open-source operating system designed for desktop use.  
It features a native GUI, custom file system, and POSIX-compatible APIs.  
To install it, download the ISO from the official website and boot it using a virtual machine or real hardware.  
Follow the installer instructions to set up partitions and complete the installation.  
The OS is ideal for experimenting with low-level system programming.

## b. System Call (Using `recv()` in Syllable OS)

The `recv()` system call is used in Syllable OS to receive data from a connected socket.  
It is part of the OS’s POSIX-style socket API.  
Developers use it in C or C++ to handle incoming data in network applications.  
The call reads bytes from the socket into a buffer and returns the number of bytes read.  
It's essential for building networked services like chat servers or web clients in Syllable OS.
