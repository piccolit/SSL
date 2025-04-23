Compilador y version del mismo:
gcc version 13.2.0

C:\Users\thiag>echo "" | gcc -dM -E -x c -std=c2x - | findstr __STDC_VERSION__
#define __STDC_VERSION__ 202000L

Version: C2X
