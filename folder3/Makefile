CC = gcc   # flag for impleict rule
CFLAG = -g  #flag for implict rule, turn the debug mode

# Impleict rule 1: blah is build via C linker implict rule
# Implicit rule 2: blag.o is built via the compilation implicit rule because blah.c exits.
blah: blah.o

blah.c:
	echo "int main(){return 0;}" > blah.c

clean:
	rm -f blah*
