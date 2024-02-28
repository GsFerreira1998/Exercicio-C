Programa de Cálculo da Área de um Triângulo Retângulo

Você foi encarregado de desenvolver um programa em C que calcula a área de um triângulo retângulo, dado os comprimentos dos seus catetos. O programa deve seguir as seguintes etapas:

Solicitar ao usuário que insira o comprimento do primeiro cateto.
Solicitar ao usuário que insira o comprimento do segundo cateto.
Calcular a área do triângulo retângulo utilizando a fórmula: área = (cateto1 * cateto2) / 2.
Exibir o resultado da área calculada com duas casas decimais.
Para melhorar a apresentação do programa, inclua um cabeçalho indicando sua funcionalidade.

Lembre-se de utilizar a localização adequada para formatação de saída em português.

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
