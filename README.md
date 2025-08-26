# CodigosC
Repositório com códigos em C desenvolvido para estudos


//idade e ano de nascimento


#include <stdlib.h>

#include <stdio.h>

int main()
{
	char nome[100];
 
	int idade,anonascimento;
 
	printf("Digite seu nome: ");
 
    fflush(stdin);
    fgets(nome,100, stdin);
    
	printf("Digite sua idade: ");
	scanf("%d", &idade);
 
	anonascimento = 2025 - idade;
	     
	     
	printf("nome do usuario: %s ", nome);
    printf("ano de nascimento: %d ", anonascimento);



	return 0;
}
