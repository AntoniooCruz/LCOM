# Makefile for lab3

COMPILER_TYPE= gnu

CC= gcc

PROG= lab3
SRCS= lab3.c test3.c keyboard.c kbd_asm.S

CFLAGS= -Wall

DPADD+= ${LIBDRIVER} ${LIBSYS}
LDADD+= -ldriver -lsys

LDFLAGS+= -L .

CPPFLAGS += -D LAB3

MAN=

.include <bsd.prog.mk>
.include <bsd.gcc.mk>
