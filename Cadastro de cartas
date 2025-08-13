#include <stdio.h>
#include <string.h>

struct Carta {


    char estado[5];
    char codigo_carta[5];
    char nome_cidade[50];
    int populacao;
    float area;
    float pib;
    int pontos_turisticos;
};

int main() {

    struct Carta carta1, carta2;


    
     printf("--- Cadastro da Primeira Carta ---\n");
    printf("Estado: ");
    scanf("%s", carta1.estado);
    printf("Codigo da carta: ");
      scanf("%s", carta1.codigo_carta);
    printf("Nome da cidade: ");
    getchar(); 
     fgets(carta1.nome_cidade, 50, stdin);
    carta1.nome_cidade[strcspn(carta1.nome_cidade, "\n")] = 0;
    printf("Populacao: ");
    scanf("%d", &carta1.populacao);
    printf("Area: ");
    scanf("%f", &carta1.area);
    printf("PIB: ");
     scanf("%f", &carta1.pib);
    printf("Pontos turisticos: ");
    scanf("%d", &carta1.pontos_turisticos);

    
    printf("\n--- Cadastro da Segunda Carta ---\n");
    printf("Estado: ");
    scanf("%s", carta2.estado);
    printf("Codigo da carta: ");
    scanf("%s", carta2.codigo_carta);
    printf("Nome da cidade: ");
      getchar();

    fgets(carta2.nome_cidade, 50, stdin);
    carta2.nome_cidade[strcspn(carta2.nome_cidade, "\n")] = 0;
     printf("Populacao: ");
    scanf("%d", &carta2.populacao);
    printf("Area: ");
    scanf("%f", &carta2.area);
     printf("PIB: ");
    scanf("%f", &carta2.pib);
    printf("Pontos turisticos: ");
    scanf("%d", &carta2.pontos_turisticos);

  
    printf("\n--- Comparando por POPULACAO ---\n");


    if (carta1.populacao > carta2.populacao) {
        printf("A carta de %s vence com %d habitantes!\n", carta1.nome_cidade, carta1.populacao);
    } else if (carta2.populacao > carta1.populacao) {
        printf("A carta de %s vence com %d habitantes!\n", carta2.nome_cidade, carta2.populacao);
    } else {
        printf("Empate na populacao!\n");
    }

    return 0;
}
