INCS = -I../../include 
LIBS = -lshp
CFLAGS = -g
LDFLAGS = -L../../bin 
OBJS = main.o
TARGET = ../../bin/voronoi-shp

all: $(OBJS)
	g++ $(LDFLAGS) $(LIBS) $(OBJS) -o $(TARGET) 

.cpp.o:
	g++ $(INCS) $(CFLAGS) -c $< -o $@

shapefile.o: ../../include/voronoi_quadtree.h

clean:
	rm *.o $(TARGET) 


