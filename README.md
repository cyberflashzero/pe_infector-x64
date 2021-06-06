# peinfect-x64
PE infector. Just enter path of a pe file in main.c. Shellcode is so big, because it was wriiten in c myself. There is asm file of shellcode too.

TO COMPILE shellcode:
  ml64 /link /entry:AlignRSP
