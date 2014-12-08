
all:
	gcc light.c -lasound -lwiringPi -g -Wall -o light

inst: all
	sudo cp light /usr/sbin
	sudo chmod 700 /usr/sbin/light
	sudo chown root /usr/sbin/light


