CXXFLAGS =	-O2 -g -Wall -fmessage-length=0

OBJS =		C++Gradle.o

LIBS =

TARGET =	C++Gradle

$(TARGET):	$(OBJS)
	$(CXX) -o $(TARGET) $(OBJS) $(LIBS)

all:	$(TARGET)

clean:
	rm -f $(OBJS) $(TARGET)
