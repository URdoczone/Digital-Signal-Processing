PWD = $(shell pwd)

LIBS = -lGL -lglut

SRCS = $(wildcard *.c)
TARGET = $(SRCS:%.c=%)

all: $(TARGET)
	@echo $(TARGET)

$(TARGET): %: %.c
	$(CC) -o $@ $< $(LIBS)

clean:
	rm -rf $(TARGET)
