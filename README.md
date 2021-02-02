# linux-uwu-configs

These configs use the following optimizations that are not enabled by default in Debian's default kernel config:

* Preemtible kernel

* Native optimizations detected by GCC (courtesy of graysky2's [gcc optimization patch](https://github.com/graysky2/kernel_gcc_patch))

* -O3 optimizations

* 1000Hz timer frequency

Note: These configs are inteded to be used with the [linux-uwu](https://github.com/mikoxyz/linux-uwu) kernel sources on Debian sid, but they'll most likely work just fine with a similarily patched kernel (provided that you run ``make oldconfig`` beforehand) with any distro (as long as you adjust any of the potentiak Debian-specific configs).

Note regarding the license: The Linux defconfigs (which I assume is what the Debian configs are based on) don't have a license attatched to them, so I assume they use GPLv2. Please open an issue if this is incorrect and I'll fix it asap.
