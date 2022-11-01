algoritmo-s
Raios

#include <stdio.h>
int raio;
float esfera;
int main()
{
    printf("digite o valor do raio ");
    scanf("%d",&raio);
    printf("\no raio é %d\n",raio);
    esfera=(4.0/3.0)*4.14159*raio*raio*raio;
    printf("\nEo volume da esfera é %f\n",esfera);
    

    return 0;
}
