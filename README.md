# LCTHW
This is about Learn C the Hard Way. I'm writing something for this ebook in order to learn C deeply.

## Notes
1. ex1.c

```c
#include <stdio.h>

int main(int argc, char *argsv[]) {
    int distance = 100;

    printf("distance: %d\n", distance);

    return 0
}
```
ex1.c just a demo of C, we can test our build tools by building this demo.

2. Makefile
```Makefile
CFLAGS=-Wall -g

clean:
	rm -f ex1

```
it's about how to use Makefile to control the behavior of make
- CFLAGS is about the flag of make.
- clean is a diy command, it means you can diy command by editing Makefile and use `make` + `DiyCommandName`, such as clean in this Makefile.