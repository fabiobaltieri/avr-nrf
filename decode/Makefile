CFLAGS = -Wall -g
LDFLAGS = -lusb

decode: nrf_frames.h decode.o opendevice.o net.o mcast.o

.PHONY: clean
clean:
	rm -f *.o decode
