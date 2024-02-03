# MIPS-Assembly-Programs - CSE-S2

Few programs written in Nasm

# Assembling
nasm -f elf sample.asm
This creates an object file, sample.o in the current directory.

# Creation of executable file
ld -melf_i386 sample.o -o test_file
This creates an executable file of the name test_file.

# Program execution
./test_file
For example, if the program to be run is palindrome.asm
nasm -f elf palindrome.asm
ld palindrome.o -o test
./test
