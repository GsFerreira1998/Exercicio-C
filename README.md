# Exercicio-C


#include <stdlib.h>
#include <stdio.h>
#include <locale.h>

int main()
{
	setlocale(LC_ALL, "portuguese"); 
	float cateto1, cateto2, area;
	printf("xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx\n");
	printf("Programa que calcula os valores dos catetos de um triangulo retangulo\n");
	printf("xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx\n");
	printf("digite o valor do cateto1:");
	scanf("%f", &cateto1);
	printf("digite o valor do cateto2:");
	scanf("%f", &cateto2);
	area = (cateto1*cateto2) /2 ; 
	printf("O Valor da area do triangulo retangulo é: %.2f \n", area);
	system("pause");
	return 0;

}
