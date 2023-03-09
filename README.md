# Assembly_Learning<br>
Learning ASM<br>
Tutorial:<br>
Linux:<br>
      Debian: sudo apt install nasm<br>
      Arch: sudo pacman -Sy nasm<br>
      RedHat: sudo yum install nasm<br>
After installing nasm assembler<br>
$ nasm -f elf64 -o filename.o filename.s<br>
$ ld -o output filename.o<br>
$ ./output<br>
