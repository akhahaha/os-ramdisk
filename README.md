OS Ramdisk
===================
	UCLA CS 111 Lab 2
	Professor Peter Reiher
	Winter 2014

	Alan Kha        904030522	akhahaha@gmail.com
	Braden Anderson 203744563	bradencanderson@gmail.com
-------------------------------------------------------------------------------
Summary
---------------
Implements a ramdisk supporting read/write and locking operations.

Features
---------------
- Supports read/write operations
- Use blocking and nonblocking locks with -l and -L options, respectively
- Performs basic self-deadlock checks

Installation
---------------
1. Extract into CS 111 Ubuntu distribution.
2. Run in QEMU emulator with ./run-qemu.

Limitations
---------------
- Does not check for deadlocks involving multiple processes and files.
