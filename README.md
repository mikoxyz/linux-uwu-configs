# linux-uwu-configs

These configs use the following optimizations that are not enabled by default in Debian's default kernel config:

* Preemtible kernel

* Native optimizations detected by GCC (courtesy of graysky2's [gcc optimization patch](https://github.com/graysky2/kernel_gcc_patch).)

* 1000Hz timer frequency

Note: These configs are inteded to be used with the [linux-uwu](https://github.com/mikoxyz/linux-uwu) kernel sources on Debian sid, but they'll most likely work just fine with a similarily patched kernel (provided that you run ``make oldconfig`` beforehand) with any distro (as long as you adjust any of the potentiak Debian-specific configs).

