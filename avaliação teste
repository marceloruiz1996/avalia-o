
#include <stdio.h>

unsigned long long fatorial(int n) 
    {
    unsigned long long resultado = 1;
    for (int i = 1; i <= n; i++)
        {
        resultado *= i;
        }
    
    return resultado;
    }
void verificar_alistamento(int ano_nasc, char sexo)
    {
    int ano_atu = 2025;
    int idade = ano_atu - ano_nasc;

    printf("\nidade: %d\n", idade);

    if (sexo == 'M' || sexo == 'm') 
        {
        if (idade >= 18) 
            {
            printf("você poderá se alistar.\n");
            }
        else
            {
            printf("você não poderá se alistar.\n");
            }
        }   
    else if (sexo == 'F' || sexo == 'f') 
        {
        printf("mulheres não são obrigadas a se alistar.\n");
        } 
    else 
        {
        printf("sexo inválido! Informe 'M' para masculino ou 'F' para feminino.\n");
        }
    }

int main()
{
   int dia, mes, ano, numero, a, b, c, d, e, temp,n, num = 2, primo1, primo2, i, contador = 0,ano_nas; 
   char sexo;
    
    printf("ex1\n\n");
    
    printf("pré definidos são variavel de controle, como int, char, float, diferença pré definidas que são para controle e já são reservada,");
    printf("\nidentificacores são variavel que programor escolhe o nome e nao são definidas");
     
    printf("\n\nex2\n\n");
    
     printf("digite o dia do seu nascimento: ");
    scanf("%d", &dia);
    printf("digite o mês do seu nascimento: ");
    scanf("%d", &mes);
    printf("digite o ano do seu nascimento: ");
    scanf("%d", &ano);
    printf("sua data de nascimento é: %02d/%02d/%04d\n", dia, mes, ano);
    
    printf("\n\nex3\n\n");
    
    printf("digite um número inteiro: ");
    scanf("%d", &numero);

    if (numero < 0) 
        {
        printf("fatorial não é definido para números negativos.\n");
        } else 
        {
        printf("o fatorial de %d é %llu\n", numero, fatorial(numero));
        }
    
    printf("\n\nex4\n\n");
    printf("Digite cinco valores inteiros:\n");
    scanf("%d %d %d %d %d", &a, &b, &c, &d, &e);

    if (a > b) { temp = a; a = b; b = temp; }
    if (b > c) { temp = b; b = c; c = temp; }
    if (c > d) { temp = c; c = d; d = temp; }
    if (d > e) { temp = d; d = e; e = temp; }

    if (a > b) { temp = a; a = b; b = temp; }
    if (b > c) { temp = b; b = c; c = temp; }
    if (c > d) { temp = c; c = d; d = temp; }

    if (a > b) { temp = a; a = b; b = temp; }
    if (b > c) { temp = b; b = c; c = temp; }

    if (a > b) { temp = a; a = b; b = temp; }

    
    printf("\nordem crescente: %d, %d, %d, %d, %d\n", a, b, c, d, e);
    printf("\nordem decrescente: %d, %d, %d, %d, %d\n", e, d, c, b, a);
    
    printf("\n\nex5\n\n");
    printf("digite o número de pares de primos gêmeos que deseja encontrar: ");
    scanf("%d", &n);

    while (contador < n) 
        {
        int isPrimo1 = 1;
        for (i = 2; i * i <= num; i++) 
            {
            if (num % i == 0)
                {
                isPrimo1 = 0;
                break;
                }
            }
        int isPrimo2 = 1; 
        for (i = 2; i * i <= (num + 2); i++) 
            {
            if ((num + 2) % i == 0)
                {
                isPrimo2 = 0;
                break;
                }
            }
        if (isPrimo1 == 1 && isPrimo2 == 1) 
            {
            printf("par de primos gêmeos: (%d, %d)\n", num, num + 2);
            contador++;
            }
        num++;
        }
        
    printf("\n\nex6\n\n");
    printf("alistamento militar.\n\n");
    printf("informe seu ano de nascimento: ");
    scanf("%d", &ano_nasc);
    printf("informe seu sexo (M para masculino, F para feminino): ");
    scanf(" %c", &sexo); 
    verificar_alistamento(ano_nasc, sexo);
    
    printf("\n\nex7\n\n");
    
    
    
    return 0;
}
