obj-m := hello.o

all:
	make -C /home/Viacheslav/repos/linux-stable M=$(PWD) ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- modules

clean:
	make -C /home/Viacheslav/repos/linux-stable M=$(PWD) clean
