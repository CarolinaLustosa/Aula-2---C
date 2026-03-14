# Aula-2---C

#include <stdio.h>

int main(){
	/* char nome[] = "Carolina Lustosa";
	int idade = 22;
	float salario = 25,89f;
	
	printf("Bom dia, %s \n", nome);
	printf("Voce tem %d anos de idade \n", idade);
	printf("Seu salario e %.2f, seu pobre", salario); */
	
// --------------------------------------	
	
	/*
	char nomeCompleto[100];
	char primeiroNome[30];
	
	printf("Digite seu primeiro nome\n");
	scanf("%s", &primeiroNome);
	printf("Seu primeiro nome e %s\n", primeiroNome);
	// deu um errinho aqui, depois pesquisar
	printf("Digite seu nome completo\n");
	fgets(nomeCompleto, sizeof(nomeCompleto), stdin);
	// fgets(variavel, sizeof(variavel), stdin);
	printf("Seu nome completo e %s\n", nomeCompleto);
	*/
	
	
	// Estrutura de seleção (if)
	
	/*
	int nota;
	scanf("%d", &nota);
	printf("Digite sua nota");
	if (nota >= 5 && nota <= 10){
		printf("Aprovado\n");
	} else {
		printf("reprovado\n");
	};
	*/
	
	/*
	int nota1, nota2;
	printf("Digite sua primeira nota\n");
	scanf("%d", &nota1);
	
	printf("Digite sua segunda nota\n");
	scanf("%d", &nota2);
	
	float media;
	media = nota1+nota2/2;

	if (media >= 7){
		printf("Aprovado");
	} else {
		if (media >= 4){
			printf("Prova final");	
		} else {
			printf("Reprovado");
		}
	};
	*/
	
	// Switch
	
	/*
	switch (expr1) {
		case constante1:
			comando1;
			break;
		case constante2:
			comando2;
			break;
		default:
			comando3;
	};
	*/
	
	
	// 7. Lista 2

/*
int numSort, palpite;

srand(time(NULL));
numSort = (rand() %5) + 1;
printf("Digite o numero do seu palpite (de 1 a 5):\n");
scanf("%d", &palpite);
if (palpite == numSort){
	printf("Voce acertou");
} else {
	printf("Voce errou, o numero era %d", numSort);
}
*/
