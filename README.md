#include <stdio.h>

int main(){
    int anoescolar[4];
    anoescolar[0] = 45;
    anoescolar[1] = 55;
    anoescolar[2] = 65;
    anoescolar[3] = 75;
    int i = 0;
    int soma = 0;
    while(i <= 3){
        printf("A posição %i do vetor armazena: %i \n", i, anoescolar[i]);
        soma += anoescolar[i];
        i++;
    }
   printf("A média simples é: %i \n", (soma / 5));
    return 0;
}
