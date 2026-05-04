#include <stdio.h>

void analisar_idade(int idade)
{
    if (idade >= 18)
        printf("bom\n");
    else
        printf("normal\n");
}

int main(void)
{
    analisar_idade(24);
}
