obj-m = pid_n_socket_scan.o
CC = gcc
PWD=$(shell pwd)

all:
	make -C /lib/modules/$(shell uname -r)/build/ M=$(PWD) modules

clean:
	rm -rf *.o *.ko Module.* modules.* *.mod.c .* *~
