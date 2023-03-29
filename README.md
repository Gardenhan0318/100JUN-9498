# 100JUN-9498
STUDY
#include <stdio.h>

int main(void) {

	int grade=0;

	printf("Test Score:");
	scanf("%d", &grade);

	if (90 <= grade && grade <= 100)
	{
		printf("Test Grade:A");
     }
	else if (80<= grade && grade <= 89)
	{
		printf("Test Grade:B");
	}
	else if (70 <= grade && grade <= 79)
	{
		printf("Test Grade:C");
	}
	else if (70 <= grade && grade <= 69)
	{
		printf("Test Grade:D");
	}
	else
	{
		printf("Test Grade:F");
	}
 
	return 0;
}
