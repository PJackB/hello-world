#include<stdio.h>

int getCommenMultiple(int x, int y) {
	if (x%y == 0)
		return x;
	else
		return getCommenMultiple(y, x%y) / (x%y)*x;
}
