#include <stdio.h>

int main() {
	int a = 1,b=0,c=1,d;
	d=(a-- && ++b && --c);
	printf("%d %d %d %d",a,b,c,d);
}
