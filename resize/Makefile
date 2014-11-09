all: resize

resize: resize.c
	gcc -o $@ $?

install: resize
	cp resize ~/bin
	cp 10-resize.sh ~/.startup.d
