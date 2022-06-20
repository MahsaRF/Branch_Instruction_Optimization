INCDIR = -I. -I/opt/papi/5.7.0/include
DBG    = -Wall 
OPT    = -O3
CC     = gcc
CPP    = g++
CFLAGS = $(DBG) $(OPT) $(INCDIR)
LDFLAGS = -lm -L/opt/papi/5.7.0/lib64 -lpapi #-lperfctr

OBJ =   minmax.o	


HEADER =  minmax.h

.SUFFIXES: .o.cpp .o.c

all: minmax

minmax: $(OBJ)
	$(CPP) $(CFLAGS) -o minmax $(OBJ)  $(LDFLAGS)

$(OBJ): 
.cpp.o: $(HEADER)
	$(CPP) $(CFLAGS) -c $< -o $@
.c.o:   $(HEADER)
	$(CC) $(CFLAGS) -c $<



clean:
	/bin/rm -f minmax *.o
	/bin/rm -f *~ 



