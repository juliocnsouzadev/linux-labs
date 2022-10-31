# Linux Kernel

- The Linux kernel is monolithic, this means that the kernel carrries out CPU scheduling, memory management and several operations by itselfs. 
- The Linux Kernel is also modular, which means it can extends its capabilities through the use of dynamically loaded kernel modules

## The Kernel is responsible for 4 major tasks

1. Memory Management
1. Process Management
1. Device Drivers
1. System calls and Security

## Linux Kernel Versions

Use **`uname`** command to get the information about the kernel (by itself it doesn't provide much information except that the system uses the **`Linux`** Kernel.
```
$ uname
```

Use the **`uname -r`** or **`uname`** comamnd and option to print the kernel version
```
$ uname -r
$ uname -a
```

## Kernel and User Space

### One of the important functions of the linux kernel is the **`Memory Management`** .

Memory is divded into two areas.
1. Kernel Space
   1. Kernel Code
   1. kernel Extensions
   1. Device Drivers
2. User Space
   1. C
   1. Java
   1. Python
   1. Ruby e.t.c
   1. Docker Containers


