/* deneme-öğrenci */
#include<stdio.h>
int main()
{
	int a[2][3]={2,1,3,2,3,4};
	printf("pointer gösterimi:\n");
	printf("%d %d %d \n",*(*(a+0)+0),*(*(a+0)+1),*(*(a+0)+2));
	printf("diğer gösterimi:\n");
	printf("%d %d %d \n",*(a[1]+0),*(a[1]+1),*(a[1]+2));
	
return 0;
}
