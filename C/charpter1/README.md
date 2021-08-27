# Development Environment Configuration
## step1:
download MinGW
## step2:
add to MinGW\mingw64\bin to environment variable PATH
# Programing Execution
## step1:
create c file,such as prog1.c
```
#include <stdio.h>
int main(void)
{
    printf("program is on.\n");
    return 0;
}
```
## step2:
compile c file and will generate a.exe file
```
gcc prog1.c
```
or use -o parameter to rename file name
```
gcc prog1.c -o prog1
```
## step3:
run a.exe
```
a.exe
```
## end
