# Haciendo un cuadrado en c 

>código:

```c
#include <stdio.h>

int main(void)
{
	int b,h;

	printf("Especifica la altura de tu cuadrado: ");
	scanf("%i", &h);
	printf("\n");
	printf("Especifica la base de tu cuadrado: ");
	scanf("%i", &b);
		for (int r = 1; r <=h; r++)
		{
			for (int l = 1; l <=b; l++)
			{
				printf(" + ");
			}
			printf("\n");
		}
		

	return (0);
}