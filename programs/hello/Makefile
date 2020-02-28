# paths
MODULES = 
INCLUDE = 

# Compile options. Το -I<dir> λέει στον compiler να αναζητήσει εκεί include files
CFLAGS = -g

# Αρχεία .o
OBJS = hello.o

# Το εκτελέσιμο πρόγραμμα
EXEC = hello

# Παράμετροι για δοκιμαστική εκτέλεση
ARGS = 

$(EXEC): $(OBJS)
	gcc $(OBJS) -o $(EXEC)

clean:
	rm -f $(OBJS) $(EXEC)

run: $(EXEC)
	./$(EXEC) $(ARGS)