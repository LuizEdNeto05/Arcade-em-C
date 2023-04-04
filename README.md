#include<stdio.h>
#include<stdlib.h>
#include<time.h>
#include<stdbool.h>
#include<locale.h>

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
printf("*               GIRAS ARCADE               *\n");
printf("*                                          *\n");
printf("*    Escolha o que desejas jogar           *\n");
printf("*                                          *\n");
printf("*    1) Perguntas e respostas              *\n");
printf("*    2) Cobra na caixa                     *\n");
printf("*    3) Gousmas War                        *\n");
printf("*    4) Sair                               *\n");
printf("*                                          *\n");
printf("*                                          *\n");
printf("********************************************\n");
printf("*                                          *\n");
printf("*                 ARCADE                   *\n");
printf("*                                          *\n");
printf("********************************************\n");
printf("*                                          *\n");
printf("*         *                   *            *\n");
printf("*        * *                  |            *\n");
printf("*         *                                *\n");
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
		int acertos, erros;
	
	acertos = 0;
	erros = 0;	
		printf("\nJOGO DE PERGUNTAS E RESPOSTA\n\n");
		printf("Erros: %i\n", erros);
		printf("Acertos: %i\n\n", acertos);
		printf("PERGUNTA 1: QUEM EH CONSIDERADO O PAI DA COMPUTACAO?\n");
		printf("a)Alan Turing\n");
		printf("b)Albert Einstein\n");
		printf("c)Werner Heisenberg\n");
		printf("d)Marie Curie\n");
		fflush(stdin);
		scanf("%c",&r);
		system("cls");
		if(r == 'a' || r == 'A'){
			acertos++;
			printf("\nVOCE ACERTOU!\n\n");
			
		}
		else {
			erros++;
			printf("\nVOCE ERROU :( A RESPOSTA CORRETA ERA a) Alan Turing\n\n");
			
		}
		
		fflush(stdin);
		
	    printf("Erros: %i\n", erros);
		printf("Acertos: %i\n\n", acertos);
		printf("PERGUNTA 2: QUEM ERA O LIDER DA UNIAO SOVIETICA DURANTE A SEGUNDA GUERRA?\n");
		printf("a)Jair Bolsonaro\n");
		printf("b)Josef Stalin\n");
		printf("c)Winston Churchill\n");
		printf("d)Adolf Hitler\n");
		fflush(stdin);
		scanf("%c",&r);
		system("cls");
		if(r == 'b' || r == 'B'){
			acertos++;
			printf("\nVOCE ACERTOU!\n\n");
			
		}
		else { 
		erros++;
			printf("\nVOCE ERROU :( A RESPOSTA CORRETA ERA b) Josef Stalin\n\n");
			
	 }
		
		printf("Erros: %i\n", erros);
		printf("Acertos: %i\n\n", acertos);
		printf("PERGUNTA 3: QUAL A CAPITAL DA ROMENIA?\n");
		printf("a)Varsovia\n");
		printf("b)Budapeste\n");
		printf("c)Brasilia\n");
		printf("d)Bucareste\n");
		fflush(stdin);
		scanf("%c",&r);
		system("cls");
		if(r == 'd' || r == 'D'){
			acertos++;
			printf("\nVOCE ACERTOU!\n\n");
			
		}
		else if(r == 'a' || r == 'b' || r == 'c') {
			erros++;
			printf("\nVOCE ERROU :( A RESPOSTA CORRETA ERA d) Bucareste\n\n");
			
		}else{
			printf("Resposta invalida");
		}
		printf("Erros: %i\n", erros);
		printf("Acertos: %i\n\n", acertos);
		printf("PERGUNTA 4: QUAL E O NUMERO DO CESUPA ARGO?\n");
		printf("a)980\n");
		printf("b)1523\n");
		printf("c)1416\n");
		printf("d)2023\n\n");
		fflush(stdin);
		scanf("%c",&r);
		system("cls");
		if(r == 'B' || r == 'b'){
			acertos++;
			printf("\nVOCE ACERTOU!\n\n");
			
		}
		else{
			erros++;
			printf("\nVOCE ERROU :( A RESPOSTA CORRETA ERA b) 1523\n\n");
			
		}
		printf("Erros: %i\n", erros);
		printf("Acertos: %i\n\n", acertos);
		printf("PERGUNTA 5: QUEM DESCOBRIU O BRASIL?\n");
		printf("a)Pedro Girotto\n");
		printf("b)Julio Cesar\n");
		printf("c)Pedro Alvares Cabral\n");
		printf("d)Alexandre, o Grande\n");
		fflush(stdin);
		scanf("%c",&r);
		if(r == 'c' || r == 'C'){
			acertos++;
			printf("\nVOCE ACERTOU!\n\n");
			
		}
		else{
			erros++;
			printf("\nVOCE ERROU :( A RESPOSTA CORRETA ERA c) Pedro alvares Cabral\n\n");
			
		} 
		printf("\nTotal de erros: %i\n", erros);
		printf("Total de acertos: %i\n\n", acertos);
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
	int escolha;
	int x;
	char jogador;
	char comece;
	char p1[40];
	char p2[40];
	
	
	srand(time(0));
	
	printf("Bem vindo ao jogo Cobra na Caixa.\n");
	
	printf("Escolha o nome do jogador 1:\n");
	fflush(stdin);
	gets(p1);
	printf("\nEscolha o nome do jogador 2:\n");
	gets(p2);
	
	system("cls");
	
	printf("Voces estao explorando a tumba do farao Neebe,\n o lesado do %s aperta um botao, fazendo com que voces caiam em um armadilha\n", p1);
	printf("%s avista que as portas que estavam para sair acabaram fechando, deixando voces dois presos\n", p2);
	printf("5 caixas aparecem na frente de voces, uma delas contem um BOTAO para a saida\n");
	printf("Uma contem tambem uma cobra MORTAL.\n\n");
	
	fflush(stdin);
	
	printf("Aperte ZERO (0) para comecar\n");
	scanf("%c", &comece);
	
	
	
	if(comece == '0'){
		system("cls");
		fflush(stdin);
		
		while(1){
			int jogador_atual = (rand() % 2) + 1;
			printf("%s, escolha uma caixa de 1 a 5\n", jogador == 1 ? p1 : p2);
			scanf("%d", &escolha);
			
			
			
			if(escolha < 1 || escolha >5 || caixa[escolha-1] != 0){
			printf("Escolha invalida! Tente novamente.\n");			
			continue;
			}
			
			if(escolha == cobra){
				printf("A cobra estava nessa caixa, %s perdeu\n", jogador == 1 ? p1 : p2);
				break;
				}else if(escolha == botao){
				printf("O botao estava nessa caixa, %s venceu!\n", jogador == 1 ? p1 : p2);
				break;
			}else{
				printf("Nao havia nada na caixa\n");
				
				caixa[escolha-1] = 1;
														
			}
				jogador = jogador == 1 ? 2 : 1;	
		}
	}
	    printf("\nO que desejas fazer agora?\n");
	     printf("\n1)JOGAR NOVAMENTE\n2)RETORNAR AO MENU\n\n");
		 scanf("%i", &x);
		 
		 if(x == 1){
		 	
		 }else if(x == 2){
		 	break;
		 	
		 }
		
		
	}
	 break;
	 
}
	system("cls");
}

	return 0;
}
