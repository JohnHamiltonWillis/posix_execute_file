# Overview
This module provides functionality for executing files using the POSIX posix_spawn API, allowing for efficient process creation and execution in a Unix-like environment. It includes a function to run executable files or shell commands, capturing the output and handling process control.

# Features
* POSIX posix_spawn Implementation: Uses the posix_spawn function for creating and managing child processes, providing a lightweight alternative to fork and exec.
* Execution Monitoring: Monitors the status of the child process, including handling signals and ensuring proper cleanup of resources.
* STDOUT Capture: Redirects and captures the standard output of the executed command for further processing.

# Requirements
* Unix-like operating system with POSIX support.
* C++11 or later.

# Usage
This module is suitable for scenarios requiring process control and execution, such as executing shell commands or running external programs from within C++ applications.
