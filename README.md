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
	
	
	
	
	// Lista de exercicios 1
	
	// 1. Fazer um algoritmo para somar 2 números inteiros lidos pelo teclado.
	
	/*
	printf("Escolha o primeiro numero");
	int n1 = scanf("%d", &n1);
	
	printf("Escolha o segundo numero");
	int n2 = scanf("%d", &n2);
	
	int soma = (n1+n2);
	printf("A soma dos dois numero e %d", soma);
	*/
	
	// 2.Elabore um algoritmo que receba como entrada o salário e o desconto do salário de um funcionário. Em seguida o algoritmo deve calcular o salário liquido do funcionário utilizando a formula Salário liquido = salário – desconto. 
	// Como saída, o algoritmo deve mostrar no vídeo o salário líquido.

	/*
	float salario, desconto, liquido;
	printf("Diga seu salario\n");
	scanf("%f", &salario);
	
	printf("Diga o desconto a ser aplicado\n");
	scanf("%f", &desconto);
	
	liquido = salario-desconto;
	printf("Seu salario liquido e %.2f\n", liquido);
	*/
		
	// 3. Escrever um algoritmo para calcular a média de 3 números dados lidos pelo teclado.
	
	/*
	printf ("Digite o primeiro numero \n");
	int number1 = scanf("%d", &number1);
	
	printf ("Digite o segundo numero \n");
	int number2 = scanf("%d", &number2);
	
	printf ("Digite o terceiro numero \n");
	int number3 = scanf("%d", &number3);
	
	int media = (number1+number2+number3/3);
	printf("A media dos tres numeros e %d \n", media);
	*/

	// 4. Elabore um algoritmo que leia como entrada um valor inteiro representando a hora (1,2,3…24) de um relógio. Em seguida o algoritmo de converter a hora lida emminutos utilizando a formula Minutos = hora * 60. 
	// Por fim o algoritmo deve mostrar no vídeo a hora lida e a hora convertida em minutos.

	/*
	int hora, minutos;
	printf("Que horas sao\n");
	scanf("%d", &hora);
	
	minutos = hora*60;
	printf("Agora sao %d horas, ou %d minutos", hora, minutos);
	*/

	// 5. Refaça o exercício anterior para que a hora agora seja um valor não inteiro (float).
	
	/*
	float hora, minutos;
	printf("Que horas sao\n");
	scanf("%f", &hora);
	
	minutos = hora*60.00;
	printf("Agora sao %.2f horas, ou %.2f minutos", hora, minutos);
	*/
	
	// 6.Faça um programa que recebe um valor de temperatura em Fahrenheit e mostre-o na tela em grau Celsius (fórmula: C = 5/9*(F-32)).
	
	/*
	float far,celsius;
	printf("Digite a temperatura em Fahrenheit\n");
	scanf("%f", &far);
	celsius = (5.0/9.0*(far-32.0));
	
	printf("A temperatura em Fahrenheit %.2f e em Celsiu e %.2f \n", far, celsius);
	*/
	
	// 7. Um professor atribui pesos de 1 a 4 para as notas de quatro avaliações. A nota é calculada por meio da média ponderada (N1 + N2*2 + N3*3 + N4*4)/10, onde N1 é a nota da primeira avaliação, N2 a da segunda, etc. 
	// Um aluno tirou as seguintes notas: 8 - 7,5 - 10 - 9. Faça um programa que calcula e mostra as notas e a média deste aluno.
	
	/*
	float mediaPonderada, n1, n2, n3, n4;
	n1 = 8.00;
	n2 = 7.50;
	n3 = 10.0;
	n4 = 9.00;
	
	mediaPonderada = n1+n2+n3+n4/4;
	printf("As notas foram %.2f, %.2f, %.2f e %.2f, e a media ponderada foi %.2f", n1, n2, n3, n4, mediaPonderada);
	*/
	
	// 8. Faça um programa que receba dois números do teclado (num1 e num2) e troque os valores dos dois usando uma variável auxiliar (aux).
	
	/*
	int num1, num2, aux;
	
	printf("Digite o primeiro numero\n");
	scanf("%d", &num1);
	
	printf("Digite o segundo numero\n");
	scanf("%d", &num2);
	
	printf("O primeiro numero e %d, o segundo e %d.\n", num1, num2);
	
	aux = num1;
	num1 = num2;
	num2 = aux;
	printf("Invertendo eles encontramos, %d e %d. \n", num1, num2);
	*/
	
	// 9. RACHA CUCA: Refaça o exercício da troca de valores do problema anterior SEM utilizar variável auxiliar.
	
	/*
	int num1, num2;
	
	printf("Digite o primeiro numero\n");
	scanf("%d", &num1);
	
	printf("Digite o segundo numero\n");
	scanf("%d", &num2);
	
	printf("O primeiro numero e %d, o segundo e %d.\n", num1, num2);
	
	
	printf("Invertendo eles encontramos, %d e %d. \n", num1, num2);
	*/
	
	// 10. 
	
	// 16. Grande demais pra botar aqui, abre o documento.
	
	/*
	float valor, desconto, valorFinal;
	char categoria;
	printf("Digite o valor do medicamento:\n");
	scanf("%f", &valor);
	printf("Digite a categoria do medicamento:\n");
	scanf(" %c", &categoria);
	
	switch(categoria){
		case 'A':
			desconto = valor * 0.1;
			valorFinal = valor - desconto;
			printf("O produto custa %.2f, o categoria e %c, o desconto e %.2f e o preco final e %.2f", valor, categoria, desconto, valorFinal);
			break;
		case 'B':
			desconto = valor * 0.15;
			valorFinal = valor - desconto;
			printf("O produto custa %.2f, o categoria e %c, o desconto e %.2f e o preco final e %.2f", valor, categoria, desconto, valorFinal);
			break;
		case 'C':
			desconto = valor * 0.2;
			valorFinal = valor - desconto;
			printf("O produto custa %.2f, o categoria e %c, o desconto e %.2f e o preco final e %.2f", valor, categoria, desconto, valorFinal);
			break;
	}
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

// 10. Lista 1

/*
float valor;
printf("Digite o valor da mercadoria:\n");
scanf("%f", &valor);
float entrada = (int)(valor/3) + fmodf(valor,3);
// float entrada = valor - 2*(int)(valor/3);
float parcela = (int)(valor/3);
printf("Valor da mercadoria: %.2f, a entrada: %.2f, e as parcelas %.2f", valor, entrada, parcela);
*/

// 11. Lista 1

/*
float entrada;
int hora, minuto, segundo;
printf("Digite o tempo em minutos:\n");
scanf("%f", &entrada);
hora = (int)(entrada/60);
minuto = (int)(entrada - hora*60);
segundo = (entrada - hora*60 - minuto)*60;
printf("Entrada: %.2f minutos, e equivalente a %d h %d min %d seg\n", entrada, hora, minuto, segundo);
*/

// 12. Lista 1
	
	return 0;
}
