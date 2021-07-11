# os-lab

## 1.Bochs

### (1) What is **Bochs**

> Bochs is a highly portable open source IA-32 (x86) PC emulator written in C++, that runs on most popular platforms. It includes emulation of the Intel x86 CPU, common I/O devices, and a custom BIOS. Bochs can be compiled to emulate many different x86 CPUs, from early 386 to the most recent x86-64 Intel and AMD processors which may even not reached the market yet.

### (2) How to use bochs

Available [bochs](https://bochs.sourceforge.io/) applications are provided in this repository, you can find them in the [bochs directory](https://github.com/fansuregrin/shiyanlou-oslab/tree/main/bochs) (bochs-gdb and bochs-dbg). However, they are both ELF 32-bit LSB executable. So, you  need to make sure you have libXpm.so.4 on your system. On more thing, if you use archlinux like me, you can install the [`lib32-libxpm`](https://aur.archlinux.org/packages/lib32-libxpm) package through [paru](https://github.com/morganamilo/paru) or [yay](https://github.com/Jguer/yay) from aur.

How to start bochs? Just execute the [run](https://github.com/fansuregrin/shiyanlou-oslab/blob/main/run) scipts.   

