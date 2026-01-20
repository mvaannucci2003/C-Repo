CC = gcc
CFLAGS = -Wall -Wextra -Iinclude
OBJFILES = main.o string-buffer.o
TARGET = main

all: $(TARGET)

$(TARGET): $(OBJFILES)
	$(CC) $(CFLAGS) -o $(TARGET) $(OBJFILES)


clean:
	rm --force $(OBJFILES) $(TARGET) *~
