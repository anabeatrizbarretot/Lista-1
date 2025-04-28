/******************************************************************************

Elabore um algoritmo para calcular: (𝑎 + 𝑏)^2

Casos de teste:
a) Para os números 2 e 3, o quadrado da soma é 25;
b) Para os números 7 e 5, o quadrado da soma é 144. 

*******************************************************************************/
#include <stdio.h>

int main()
{
   int a = 0, b = 0;
    int qsoma = 0;

    printf("Digite o primeiro número: ");
    scanf("%d", &a);
    printf("Digite o segundo número: ");
    scanf("%d", &b);

    qsoma = (a + b) * (a + b);

    printf("O quadrado da soma de %d e %d é %d\n", a, b, qsoma);

}
