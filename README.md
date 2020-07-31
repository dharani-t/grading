//# grading
//the program is about the grades given according to their marks
#include<stdio.h>
int main()
{
 int score;
 printf("enter your score:");
 scanf("%d",&score);
if(score>=70)
{
	if(score>=85)
	{
	printf("Grade A");
	}
	else
	{
	printf("Grade B");
	}
}
else 
{
	if(score<=69&& score>=55)
	{
		printf("Grade C");
	}
	else if(score<=54&&score>=40)
	{
		printf("Grade D");
	}
	else
    {
	  printf("Grade F");
    }

}
}
