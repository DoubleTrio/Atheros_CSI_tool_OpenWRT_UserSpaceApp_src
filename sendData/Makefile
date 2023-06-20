CC = mips-openwrt-linux-gcc

send_data: sendData.c
	$(CC) -o sendData sendData.c
	$(CC) -o sendDataLoop sendDataLoop.c

clean:
	rm -f *.o sendData sendDataLoop
		
