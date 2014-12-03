Minix3_GroupKill
================

OS Project


Group Kill() (Modified Kill())

Kill Command Modifications
To allow other members of the same group as the user to send the kill command to programs started by the user, the check for permission part of the signal.c file was modified to not send the error code EPERM when a user with the same effgid or same realgid tried to send the kill signal.

FOR MORE INFORMATION REFER TO Report.pdf

Lessons from this project
From this project I learned what effuid, realuid, effgid, and realgid mean. I also learned how the kill call checks who sent the command and if they are allowed to do so. I learned how to mount the files of the minix operating system on my windows machine to edit them using sublime. I learned how to use many commands and what they do in the minix operating system.

Biggest Challenge
The biggest challenge in this project was finding where the system call files where in the directory and how to edit them when the system was running on a virtual machine. To find them and edit them I had to learn how to mount the operating system files as a drive on my windows machine using a sftp file system.
