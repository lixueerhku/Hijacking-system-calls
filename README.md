# Hijacking-system-calls
UofT CSC369-A1: writing and installing a very basic kernel module to the Linux kernel
You will implement a new system call named my_syscall, which will allow you to send commands from userspace, 
to intercept another pre-existing system call (like read, write, open, etc.). After a system call is intercepted, 
the intercepted system call logs a message first before continuing performing what it was supposed to do.
