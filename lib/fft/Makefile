# We will build the fft and
# run main which has test cases
all:
	@mkdir -p .build
	gcc -g -O0 -Wall -Werror -c fft.c -o ./.build/fft.o
	gcc -g -O0 -Wall -Werror -c main.c -o ./.build/main.o
	gcc -g -O0 -Wall -Werror -lm ./.build/fft.o ./.build/main.o -o ./.build/fft
	./.build/fft

clean:
	rm -rf .build
