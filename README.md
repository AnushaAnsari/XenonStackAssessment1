# XenonStackAssessment1
Linux Custom Script Task
Scenario
A customer requires a custom Linux command for specific operations. Your task is to create a Linux command using a Bash script.

Command Name: internsctl
Command Version: v0.1.0
Section A
Manual Page:

Execute man internsctl to view full documentation and usage guidelines.
Help Option:

Execute internsctl --help to get usage examples.
Version:

Execute internsctl --version to display the command version.
Section B
Part 1 | Level Easy
CPU Information:

Execute $ internsctl cpu getinfo to get CPU information similar to lscpu command.
Memory Information:

Execute $ internsctl memory getinfo to get memory information similar to free command.
Part 2 | Level Intermediate
Create User:

Execute $ internsctl user create <username> to create a new user with login access.
List Users:

Execute $ internsctl user list to list all regular users.
Execute $ internsctl user list --sudo-only to list users with sudo permissions.
Part 3 | Advanced Level
File Information:
Execute $ internsctl file getinfo <file-name> to get detailed file information.
