## Atividades da aula 12 de LOP

# Atividade 1
```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#include <conio.h>
int main() {
     int numero[4][5] = {
        {5, 10, 15, 20, 25},
        {30, 35, 40, 45, 50},
        {55, 60, 65, 70, 75},
        {80, 85, 90, 95, 100}
    };
    int valor = 5;
    for(int i = 0; i < 4; i++) {
        for(int j = 0; j < 5; j++) {
            numero[i][j] = valor;
            valor += 5;
        }
    }
    for(int i = 0; i < 4; i++) {

        for(int j = 0; j < 5; j++) {
            printf("%d ", numero[i][j]);
        }
        printf("\n");
    }
    getch();
}
```
