EX 6
#include <stdio.h>

int main() {
    int idade;
    int i;

    // Loop para as 10 pessoas
    for (i = 1; i <= 10; i++) {
        printf("Pessoa %d:\n", i);

        // Entrada da idade
        printf("Digite a idade: ");
        scanf("%d", &idade);

        // Classificação da pessoa com base na idade
        if (idade >= 0 && idade <= 12) {
            printf("Criança\n");
        } else if (idade >= 13 && idade <= 17) {
            printf("Adolescente\n");
        } else if (idade >= 18 && idade <= 64) {
            printf("Adulto\n");
        } else if (idade >= 65) {
            printf("Idoso\n");
        } else {
            printf("Idade inválida\n");  // Verifica se a idade é negativa
        }
        printf("\n");  // Adiciona uma linha em branco para separar as pessoas
    }

    return 0;
}
