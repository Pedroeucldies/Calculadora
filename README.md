#Calculadora

    #include <stdio.h>
  
    int main() 
    {
    
    int num1, num2;
    int soma, subtracao, multiplicacao;
    float divisao;

    printf("Digite o primeiro número: ");
    scanf("%d", &num1);

    printf("Digite o segundo número: ");
    scanf("%d", &num2);

    soma = num1 + num2;
    printf("Soma: %d\n", soma);
    
    subtracao = num1 - num2;
    printf("Subtração: %d\n", subtracao);

    multiplicacao = num1 * num2;
    printf("Multiplicação: %d\n", multiplicacao);

    if (num2 != 0) {
        divisao = (float)num1 / num2;
        printf("Divisão: %.2f\n", divisao);
    } else {
        printf("Erro: divisão por zero\n");
    }
    return 0;}
    }
