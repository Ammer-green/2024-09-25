#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
int main()
{
	/*
	int ch = 0;
	while ((ch = getchar()) != EOF)
		putchar(ch);
	return 0;
	*/
	
	
	char password[20] = { 0 };
	printf("请输入密码");
	scanf("%s", password);
	printf("请确认密码(Y/N)\n:>");
	//清理缓冲区
	getchar();//清理\n
	int ch = getchar();                                                  //输入函数       getchar
	if (ch == 'Y')                                                       //                 scanf
		printf("确认成功\n");
	else
		printf("确认失败\n");
		

	

	return 0;
}
