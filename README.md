# Arcade-em-C

#include<stdio.h>
#include<stdlib.h>
#include<time.h>
int main(){
	int a;
	
printf("********************************************\n");
printf("*                                          *\n");
printf("*                 ARCADE                   *\n");
printf("*                                          *\n");
printf("********************************************\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("*              GIRAS ARCADE                *\n");
printf("*                                          *\n");
printf("* 1) Perguntas e respostas                 *\n");
printf("* 2) Cobra na caixa                        *\n");
printf("* 3) Gousmas War                           *\n");
printf("* 4) Sair                                  *\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("********************************************\n");
printf("*                                          *\n");
printf("*      *                         *         *\n");
printf("*     * *                        |         *\n");
printf("*      *                                   *\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("********************************************\n");
scanf("%i",&a);
switch(a){
	case 1:
		char r;
		system("cls");
		printf("\nJOGO DE PERGUNTAS E RESPOSTA\n\n");
		printf("PERGUNTA 1: QUEM DESCOBRIU O BRASIL?\n");
		printf("a)Pedro Alvares Cabral\n");
		printf("b)Pedro Girotto\n");
		printf("c)Pedro Belchior\n");
		printf("d)Pedro Henrique\n");
		fflush(stdin);
		scanf("%c",&r);
		if(r == 'a' || r == 'A'){
			printf("\nVOCE ACERTOU!\n\n");
		}
		else {
			printf("\nVOCE ERROU :(\n\n");
		}
		printf("PERGUNTA 2: QUAL O FORMATO DA TERRA?\n");
		printf("a)Redonda\n");
		printf("b)Plana\n");
		printf("c)Rosquinha\n");
		printf("d)Triangulo\n");
		fflush(stdin);
		scanf("%c",&r);
		if(r == 'a' || r == 'A'){
			printf("\nVOCE ACERTOU!\n\n");
		}
		else {
			printf("\nVOCE ERROU :(\n\n");
		}
		printf("PERGUNTA 3: QUAL A CAPITAL DO PARA?\n");
		printf("a)Ananindeua\n");
		printf("b)Grao Para\n");
		printf("c)Cotijuba\n");
		printf("d)Belem\n");
		fflush(stdin);
		scanf("%c",&r);
		if(r == 'd' || r == 'D'){
			printf("\nVOCE ACERTOU!\n\n");
		}
		else {
			printf("\nVOCE ERROU :(\n\n");
		}
		printf("PERGUNTA 4: QUEM É PEDRO GIROTTO?\n");
		printf("a)Professor de programacao do Cesupa\n");
		printf("b)Morador de Cotijuba\n");
		printf("c)Porteiro\n");
		printf("d)Advogado\n");
		fflush(stdin);
		scanf("%c",&r);
		if(r == 'a' || r == 'A'){
			printf("\nVOCE ACERTOU!\n\n");
		}
		else {
			printf("\nVOCE ERROU :(\n\n");
		}
		printf("PERGUNTA 5: Qaunto eh 1+1?\n");
		printf("a)44\n");
		printf("b)1\n");
		printf("c)2\n");
		printf("d)100\n");
		fflush(stdin);
		scanf("%c",&r);
		if(r == 'c' || r == 'C'){
			printf("\nVOCE ACERTOU!\n\n");
		}
		else {
			printf("\nVOCE ERROU :(\n\n");
		} main();
		break;
	case 2:
	char p1[40];
	char p2[40];
	
	system ("cls");
	
	printf("Bem vindo ao jogo Cobra na Caixa.\n");
	
	printf("Escolha o nome do jogador 1:\n");
	scanf("%s", &p1);
	printf("\nEscolha o nome do jogador 2:\n");
	scanf("%s", &p2);
	
	printf("Voces estao explorando uma tumba do farao Neebe, o lesado do %s aperta um botao caindo em um armadilha\n", p1);
	printf("O jogador %s avista que as portas que estava para sair acaba fechando, deixando voces presos\n", p2);
	printf("5 caixas aparecem na frente de voces, uma delas contem um BOTAO para a saida\n");
	printf("Uma contem tambem uma cobra mortal.\n");
	
	
}	
	
	
	return 0;
}
