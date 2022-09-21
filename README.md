#include<stdio.h>

//int main(void)
//{
//	int x, y, z;
//	scanf("%d%d", &x, &y);
//	z = x + y;
//	printf("%d", z);
//
//	return 0;
//}

//int main(void)
//{
//	int x, y, z;
//	scanf("%d%d%d", &x, &y, &z);
//	printf("%d\n", y);
//
//	return 0;
//}


//左对齐和右对齐
//左对齐：方式一  printf("%d\n",101010)  默认打印格式为左对齐
//        方式二  printf("%-10d\n"101010)  在打印数字宽度前面加一个“-”。
//数字宽度为10，如果要打印的位数小于10，则在后面补足空格；如果要打印的位数大于10，则打印所有的数字，不会截断。
//右对齐：在%和d之间加上数字宽度，就可以右对齐
//int main(void)
//{
//	int x, y, z;
//	scanf("%d%d%d", &x, &y, &z);
//	printf("%8d%8d%8d\t", x, y, z);
//
//	return 0;
//}


//int main(void)
//{
//	int a, b, c,d;
//	scanf("%d%d%d", &a, &b, &c);
//	d = (a + b) * c;
//	printf("%d\n", d);
//
//	return 0;
//}


//int main(void)
//{
//	int a, b;
//	double c;
//	scanf("%d%d", &a, &b);
//	c = (double)a /(double) b;
//	printf("%.9f\n", c);
//
//	return 0;
//}


//int main(void)
//{
//	double F,C;
//	scanf("%lf", &F);
//	C = 5 * (F - 32) / 9;
//	printf("%.5f\n", C);
//
//	return 0;
//}




//int main(void)
//{
//	int i, n, arr[64];
//	arr[1] = 0;
//	arr[2] = 1;
//	for (i = 3; i <= 64; i++)
//	{
//		arr[i] = arr[i - 1] + arr[i - 2];
//	}
//	scanf("%d", &n);
//	printf("%d", arr[n]);
//	return 0;
//}

#include<math.h>
//int main(void)
//{
//	double x, a, b, c, d;
//	scanf("%lf%lf%lf%lf%lf", &x, &a, &b, &c, &d);
//	double f = a *pow(x,3) + b * pow(x,2) + c * x + d;
//	printf("%.7f\n", f);
//	return 0;
//}

//int main(void)
//{
//	char a;
//	scanf("%c", &a);
//	printf("  %c\n %c%c%c\n%c%c%c%c%c\n %c%c%c\n  %c\n", a, a, a, a, a, a, a, a, a, a, a, a, a);
//
//	return 0;
//}

int main(void)
{
	int N;
	scanf("%d", &N);
	if (N > 0)
	{
		printf("positive\n");
	}
	else if (N == 0)
	{
		printf("zero\n");
	}
	else
	{
		printf("negative\n");
	}
	return 0;
}
