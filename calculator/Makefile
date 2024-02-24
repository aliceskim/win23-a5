objects = addition.o division.o main.o multiplication.o operations.o subtraction.o

calculator: addition.c division.c main.c multiplication.c operations.h subtraction.c
	g++ -o calculator addition.c division.c main.c multiplication.c operations.h subtraction.c

$(objects): %.o:%.c
	g++ -c $< -o $@

clean:
	rm -f calculator $(objects)
