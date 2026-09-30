# P01
프로그래밍응용 | 과제3 - 프로그래밍5

#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>

int main(void)
{
	int x, y;

	printf("정수 2개를 입력하시오: ");

	scanf("%d %d", &x, & y);

	printf("\n\n몫: %d\n", x/y);
	printf("나머지 %d", x%y);

	return 0;
}
