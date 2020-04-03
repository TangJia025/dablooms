all: test

test: test_dablooms.c dablooms.c murmur.c
	gcc $^ -o $@ -lm

clean:
	rm -f test
