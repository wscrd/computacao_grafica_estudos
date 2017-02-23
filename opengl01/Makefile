OS := $(shell uname)
CC = gcc
CFLAGS = -lGL -lGLU -lglut
CFLAGSOSX = -framework GLUT -framework OpenGL -framework Cocoa
ifeq ($(OS), Darwin)
  CFLAGS = CFLAGSOSX
endif
opengl_01: opengl_01.c
	$(CC) -o opengl_01 opengl_01.c $(CFLAGS)%
