CC=g++
CFLAGS=-std=c++23 -Ofast -Wall -Wextra -Wdouble-promotion -Wno-unused-parameter
BINS=bin/prog
all: clean problema

problema:
	$(CC) $(CFLAGS) -o bin/prog src/Ejercicio1_resuelto.cpp

clean:
	@echo " [CLN] Removing binary files"
	@rm -f $(BINS)
