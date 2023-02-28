calculator: main.o addition.o subtraction.o multiplication.o division.o 
	cc -o calculator main.o addition.o subtraction.o multiplication.o division.o

main.o addition.o subtraction.o multiplication.o division.o: operations.h

clean:
	rm -f calculator *.o

.PHONY: clean
