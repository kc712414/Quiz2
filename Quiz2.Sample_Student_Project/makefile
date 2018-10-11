CC = g++


all: build doczip

clean:
	-rm *.o
	-rm *.class
	-rm .out
	-rm exe
	-rm html
	-rm latex


build: *.cc *.h
	$(CC) -o myexe *.cc

doc: *.cc *.h
	doxygen Doxyfile

doczip:
	zip -r quiz2 *
 
	
