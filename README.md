# c-
2020/9/8
#include <stdio.h>


int main()
{
	int num1 = 0;
	int num2 = 0;
	int sum = 0;
	scanf("%d%d", &num1, &num2);
	sum = num1 + num2;
	printf("sum = %d\n", sum);
	return 0;
}
2020/9/9
#include <stdio.h>

int main()
{
	float num1 = 0;
	float num2 = 0;
	float sum = 0;
	char a = 'A';
	int b = 20;
	scanf("%f%f", &num1, &num2);
	sum = num1 + num2;
		printf("sum= %lf\n", sum);//十进制变二进制运算再改回是进制会有截断误差，
		//所以要用double 的 lf 来表示
		printf("%c\n", a);
		printf("%d\n", b);
		printf("大功告成\n");
		return 0;
		
