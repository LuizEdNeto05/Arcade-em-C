#include<stdio.h>
#include<stdlib.h>
#include<time.h>
#include<stdbool.h>

int main(){
	int a;
	while(1){
	
printf("********************************************\n");
printf("*                                          *\n");
printf("*                 ARCADE                   *\n");
printf("*                                          *\n");
printf("********************************************\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("*              GIRAS ARCADE                *\n");
printf("*                                          *\n");
printf("*    Escolha o que desejas jogar           *\n");
printf("*                                          *\n");
printf("*    1) Perguntas e respostas              *\n");
printf("*    2) Cobra na caixa                     *\n");
printf("*    3) Gousmas War                        *\n");
printf("*    4) Sair                               *\n");
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
		
		while(1){
		
		
		system("cls");
		char r;
		int x;
		printf("\nJOGO DE PERGUNTAS E RESPOSTA\n\n");
		printf("PERGUNTA 1: QUEM DESCOBRIU O BRASIL?\n");
		printf("a)Pedro Alvares Cabral\n");
		printf("b)Pedro Girotto\n");
		printf("c)Pedro Victor\n");
		printf("d)Pedro Henrique\n");
		fflush(stdin);
		scanf("%c",&r);
		if(r == 'a' || r == 'A'){
			printf("\nVOCE ACERTOU!\n\n");
		}
		else {
			printf("\nVOCE ERROU :(\n\n");
		}
		
		fflush(stdin);
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
		else if(r == 'a' || r == 'b' || r == 'c') {
			printf("\nVOCE ERROU :(\n\n");
		}else{
			printf("Resposta invalida");
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
		else{
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
		else{
			printf("\nVOCE ERROU :(\n\n");
		} 
		printf("VOCE TERMINOU O JOGO, O QUE VOCE PRETENDE FAZER AGORA?\n\n");
		printf("1)JOGAR NOVAMENTE\n\n2)RETORNAR AO MENU\n\n");
		scanf("%i", &x);
		if(x == 1){
			
		}else if(x == 2){
		
		break;	
		}
	}
		break;
	
	case 2:
		
		while(1){
		
	
	system ("cls");
	
	int caixa[5] = {0, 0, 0, 0, 0};
	int botao = rand() % 5;
	int cobra = rand() % 5;
	int jogador;
	int escolha;
	char comece;
	char p1[40];
	char p2[40];
	
	
	srand(time(NULL));
	
	printf("Bem vindo ao jogo Cobra na Caixa.\n");
	
	printf("Escolha o nome do jogador 1:\n");
	fflush(stdin);
	gets(p1);
	printf("\nEscolha o nome do jogador 2:\n");
	gets(p2);
	
	system("cls");
	
	printf("Voces estao explorando a tumba do farao Neebe, o lesado do %s aperta um botao, fazendo com que voces caiam em um armadilha\n", p1);
	printf("%s avista que as portas que estavam para sair acabaram fechando, deixando voces dois presos\n", p2);
	printf("5 caixas aparecem na frente de voces, uma delas contem um BOTAO para a saida\n");
	printf("Uma contem tambem uma cobra MORTAL. \n\n");
	
	fflush(stdin);
	
	printf("Aperte ZERO (0) para comecar\n");
	scanf("%c", &comece);
	
	
	if(comece == '0'){
		system("cls");
		fflush(stdin);
		
		while(1){
			printf("%s, escolha uma caixa de 1 a 5\n");
			scanf("%d", &escolha);
			
			if(escolha < 1 || escolha >5){
			printf("Escolha invalida! Tente novamente.\n");			
			continue;
			}else{
			}
		}
	}
		break;
		
	}
	
}	
	
}

	return 0;
}   
