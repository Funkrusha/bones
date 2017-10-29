all: dtbo install

dtbo:
	dtc -O dtb -o NONAME-SPITFT18-00A0.dtbo -b 0 -@ NONAME-SPITFT18-00A0.dts

install:
	cp -rp NONAME-SPITFT18-00A0.dtbo /lib/firmware/

load:
	echo NONAME-SPITFT18 > $(SLOTS)
