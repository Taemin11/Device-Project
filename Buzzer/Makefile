KERNEL_DIR = /lib/modules/4.19.57-v7+/build

obj-m := buzzer_dev.o

PWD := $(shell pwd)

all:
	make -C $(KERNEL_DIR) M=$(PWD) modules

clean:
	make -C $(KERNEL_DIR) M=$(PWD) clean
