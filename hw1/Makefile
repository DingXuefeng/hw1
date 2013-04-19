TARGET = hw1
SOURCE = hw1.cxx
CC = g++
LIBS = `root-config --libs` -lDybStyle -L/home/dingxf/lib
CFLAGS = `root-config --cflags` -I/home/dingxf/include -I../include
COMIPLEFLAGS = -fPIC -m -g -Wall -O2

all: $(TARGET)

$(TARGET): hw1.cxx
	$(CC) $(SOURCE) -o $(TARGET) $(LIBS) $(CFLAGS)

clean:
	touch $(TARGET)
	rm $(TARGET)
	rm *~
