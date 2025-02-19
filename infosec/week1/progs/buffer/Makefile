payload:
	./makePayload > input
example2:
		gcc -fno-stack-protector -z execstack -no-pie -m32 -g example2.c -o example2
example1:
		gcc -fno-stack-protector -z execstack -no-pie -m32 -g example1.c -o example1
example:
		gcc -fno-stack-protector -z execstack -no-pie -m32 -g example.c -o example
clean:
	rm -rf example1 example example2 input 
	
