CXX	=	/opt/homebrew/bin/g++-13
CXXFLAGS	=	-g -std=c++20

SRCS	=	main.cpp point.cpp
OBJS	=	$(SRCS:.cpp=.o)
TARGET	=	rooster

all:	$(TARGET)

$(TARGET):	$(OBJS)
	$(CXX) $(CXXFLAGS) $^ -o $@

# %.o:%.cpp
#     $(CXX)	$(CXXFLAGS)	-c	$<	-o	$@

clean:
	rm -f $(OBJS) $(TARGET)
