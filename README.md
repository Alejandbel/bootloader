# bootloader
To run you have to install nasm assembler and qemu vm

Run this commands
```
nasm -f bin bootloader.asm -o bootloader.bin
qemu-system-i386 -fda bootloader.bin
```
