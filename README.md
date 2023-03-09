# Assembly_Learning
Learning ASM
Tutorial:
Linux:
      Debian: sudo apt install nasm
      Arch: sudo pacman -Sy nasm
      RedHat: sudo yum install nasm
After installing nasm assembler
$ nasm -f elf64 -o filename.o filename.s
$ ld -o output filename.o
$ ./output
