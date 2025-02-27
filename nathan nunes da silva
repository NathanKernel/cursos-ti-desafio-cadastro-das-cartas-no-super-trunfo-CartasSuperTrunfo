#include <stdio.h>

int main() {
    // Declaração das variáveis para armazenar os dados das cartas
    char carta1[50], carta2[50];
    int populacao1, populacao2;
    float area1, area2, pib1, pib2;
    int pontosTuristicos1, pontosTuristicos2;

    // Entrada de dados para a primeira carta
    printf("Digite o codigo da primeira carta (ex: A01): ");
    scanf("%s", carta1);
    printf("Digite a populacao da primeira carta: ");
    scanf("%d", &populacao1);
    printf("Digite a area da primeira carta: ");
    scanf("%f", &area1);
    printf("Digite o PIB da primeira carta: ");
    scanf("%f", &pib1);
    printf("Digite o numero de pontos turisticos da primeira carta: ");
    scanf("%d", &pontosTuristicos1);

    // Entrada de dados para a segunda carta
    printf("\nDigite o codigo da segunda carta (ex: B02): ");
    scanf("%s", carta2);
    printf("Digite a populacao da segunda carta: ");
    scanf("%d", &populacao2);
    printf("Digite a area da segunda carta: ");
    scanf("%f", &area2);
    printf("Digite o PIB da segunda carta: ");
    scanf("%f", &pib2);
    printf("Digite o numero de pontos turisticos da segunda carta: ");
    scanf("%d", &pontosTuristicos2);

    // Cálculo da densidade populacional para ambas as cartas
    float densidade1 = populacao1 / area1;
    float densidade2 = populacao2 / area2;

    // Exibição dos dados cadastrados para as duas cartas
    printf("\nDados da primeira carta (%s):\n", carta1);
    printf("Populacao: %d, Area: %.2f, PIB: %.2f, Pontos turisticos: %d\n", populacao1, area1, pib1, pontosTuristicos1);
    printf("Densidade Populacional: %.2f\n", densidade1);

    printf("\nDados da segunda carta (%s):\n", carta2);
    printf("Populacao: %d, Area: %.2f, PIB: %.2f, Pontos turisticos: %d\n", populacao2, area2, pib2, pontosTuristicos2);
    printf("Densidade Populacional: %.2f\n", densidade2);

    // Menu para escolha do atributo de comparação
    int escolha;
    printf("\nEscolha o atributo para comparacao:\n");
    printf("1 - Populacao\n");
    printf("2 - Area\n");
    printf("3 - PIB\n");
    printf("4 - Pontos turisticos\n");
    printf("5 - Densidade populacional\n");
    printf("Digite o numero da sua escolha: ");
    scanf("%d", &escolha);

    // Comparação entre as cartas de acordo com a escolha do atributo
    switch(escolha) {
        case 1: { // Comparação pela População
            printf("\nComparacao de cartas (Atributo: Populacao):\n");
            printf("Carta 1 - %s: %d\n", carta1, populacao1);
            printf("Carta 2 - %s: %d\n", carta2, populacao2);
            if (populacao1 > populacao2) {
                printf("Resultado: Carta 1 (%s) venceu!\n", carta1);
            } else if (populacao2 > populacao1) {
                printf("Resultado: Carta 2 (%s) venceu!\n", carta2);
            } else {
                printf("Resultado: Empate! Ambas as cartas tem a mesma populacao.\n");
            }
            break;
        }
        case 2: { // Comparação pela Área
            printf("\nComparacao de cartas (Atributo: Area):\n");
            printf("Carta 1 - %s: %.2f\n", carta1, area1);
            printf("Carta 2 - %s: %.2f\n", carta2, area2);
            if (area1 > area2) {
                printf("Resultado: Carta 1 (%s) venceu!\n", carta1);
            } else if (area2 > area1) {
                printf("Resultado: Carta 2 (%s) venceu!\n", carta2);
            } else {
                printf("Resultado: Empate! Ambas as cartas tem a mesma area.\n");
            }
            break;
        }
        case 3: { // Comparação pelo PIB
            printf("\nComparacao de cartas (Atributo: PIB):\n");
            printf("Carta 1 - %s: %.2f\n", carta1, pib1);
            printf("Carta 2 - %s: %.2f\n", carta2, pib2);
            if (pib1 > pib2) {
                printf("Resultado: Carta 1 (%s) venceu!\n", carta1);
            } else if (pib2 > pib1) {
                printf("Resultado: Carta 2 (%s) venceu!\n", carta2);
            } else {
                printf("Resultado: Empate! Ambas as cartas tem o mesmo PIB.\n");
            }
            break;
        }
        case 4: { // Comparação pelos Pontos Turísticos
            printf("\nComparacao de cartas (Atributo: Pontos Turisticos):\n");
            printf("Carta 1 - %s: %d\n", carta1, pontosTuristicos1);
            printf("Carta 2 - %s: %d\n", carta2, pontosTuristicos2);
            if (pontosTuristicos1 > pontosTuristicos2) {
                printf("Resultado: Carta 1 (%s) venceu!\n", carta1);
            } else if (pontosTuristicos2 > pontosTuristicos1) {
                printf("Resultado: Carta 2 (%s) venceu!\n", carta2);
            } else {
                printf("Resultado: Empate! Ambas as cartas tem o mesmo numero de pontos turisticos.\n");
            }
            break;
        }
        case 5: { // Comparação pela Densidade Populacional
            printf("\nComparacao de cartas (Atributo: Densidade Populacional):\n");
            printf("Carta 1 - %s: %.2f\n", carta1, densidade1);
            printf("Carta 2 - %s: %.2f\n", carta2, densidade2);
            if (densidade1 < densidade2) { // Menor densidade vence
                printf("Resultado: Carta 1 (%s) venceu!\n", carta1);
            } else if (densidade2 < densidade1) {
                printf("Resultado: Carta 2 (%s) venceu!\n", carta2);
            } else {
                printf("Resultado: Empate! Ambas as cartas tem a mesma densidade populacional.\n");
            }
            break;
        }
        default:
            printf("Escolha invalida!\n");
            break;
    }

    return 0;
}
