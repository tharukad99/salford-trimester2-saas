#include <stdio.h>

int globalVar = 42;
static int staticVar;

void simpleFunction(){
	printf("simple function\n");
}

int main(){
	printf(" main\n");
	simpleFunction();
	return 0;
}