#source files
OBJS =

CC=g++

#Defining path for header files
INCLUDE_PATH=-I ../SDL2/i686-w64-mingw32/include/SDL2

#Defining paths for linked Libraries
LIBRARY_PATH=-L ../SDL2/i686-w64-mingw32/lib


CFLAGS= -w -Wl,-subsystem,windows

LINKERS=-lmingw32 -lSDL2main -lSDL2

OUTPUT_NAME=WireMesh

all : $(OBJS)
	$(CC) $(OBJS) $(INCLUDE_PATH) $(LIBRARY_PATH) $(CFLAGS) $(LINKERS) -o $(OUTPUT_NAME)