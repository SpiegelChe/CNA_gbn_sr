# CNA_gbn_sr

### Download gcc
    https://www.mingw-w64.org/
### Configure gcc
    unzip and add directory to system variable 'PATH'.

### Run gcc command
    gcc -Wall -ansi -pedantic -o sr emulator.c sr.c

---

### Bug fixed
1. failed to run with gcc
   ——>check installation and system variable

2. emulator.c:40:10: fatal error: gbn.h: No such file or directory
   ——>change include directory to sr.c

3. warning: ISO C90 forbids mixed declarations and code
   ——>C separates declaration and assignment

4. error: C++ style comments are not allowed in ISO C90
   ——>// needs changing to /*  */

5. error: 'for' loop initial declarations are only allowed in C99 or C11 mode
   ——>C separates declaration and assignment
