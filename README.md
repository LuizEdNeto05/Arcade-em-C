# Arcade-em-C

## Projeto
  Foi pedido para que a gente fizesse um Arcade contendo 3 jogos.
  
## Objetivo
  Colocar em prática tudo que aprendemos em sala de numa situação do cotidiano.
  
## Os Jogos

 -Jogo 1:
   Jogo de perguntas e respostas: um game que consiste em 5 perguntas com 4 alternativas cada
   e mostrando a pontuação do jogador durante e ao término da jogatina.
   
 - Jogo 2:
    Cobra na caixa: um jogo em que os jogadores terão que contar com a sorte, estarão disponíveis
    5 caixas para os dois jogadores escolherem, ganha aquele que achar o botão primeiro ou espera 
    o adversário perder com ele escolhendo a cobra.
   
 -Jogo 3:
   Gousmas War: nesse jogo, também multiplayer, 2 jogadores terão 2 gousmas que irão batalhar
   um contra o outro, ganha aquele que destruir todos os gousmas adversários primeiro.
   
## Integrantes

### Luiz Eduardo
 [![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/LuizEdNeto05)


### Renan Abreu
 [![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RenanAbreu09)


### Thiago Cardoso
 [![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ThiagoCardoso03)
 
 
 
 
 
 
 
 
 
 
 #include<stdio.h>
#include<stdlib.h>
#include<time.h>
#include<stdbool.h>
#include<locale.h>
int main(void) {
	int a,x;
	do {

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
		switch(a) {
			case 1:

				while(1) {


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
					if(r == 'a' || r == 'A') {
						acertos++;
						printf("\nVOCE ACERTOU!\n\n");

					} else {
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
					if(r == 'b' || r == 'B') {
						acertos++;
						printf("\nVOCE ACERTOU!\n\n");

					} else {
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
					if(r == 'd' || r == 'D') {
						acertos++;
						printf("\nVOCE ACERTOU!\n\n");

					} else {
						erros++;
						printf("\nVOCE ERROU :( A RESPOSTA CORRETA ERA d) Bucareste\n\n");

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
					if(r == 'B' || r == 'b') {
						acertos++;
						printf("\nVOCE ACERTOU!\n\n");

					} else {
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
					system("cls");
					if(r == 'c' || r == 'C') {
						acertos++;
						printf("\nVOCE ACERTOU!\n\n");

					} else {
						erros++;
						printf("\nVOCE ERROU :( A RESPOSTA CORRETA ERA c) Pedro alvares Cabral\n\n");

					}
					printf("\nTotal de erros: %i\n", erros);
					printf("Total de acertos: %i\n\n", acertos);
					printf("VOCE TERMINOU O JOGO, O QUE VOCE PRETENDE FAZER AGORA?\n\n");
					printf("1)JOGAR NOVAMENTE\n\n2)RETORNAR AO MENU\n\n");
					scanf("%i", &x);
					if(x == 1) {
						continue;
					} else if(x == 2) {
						system("cls");
						break;
					}
				}
				continue;

			case 2:

				while(1) {


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

					printf("Voces estao explorando a tumba do farao Neebe,\no lesado do %s aperta um botao, fazendo com que voces caiam em uma armadilha\n", p1);
					printf("%s avista que as portas que estavam para sair acabaram fechando, deixando voces dois presos\n", p2);
					printf("5 caixas aparecem na frente de voces, uma delas contem um BOTAO para a saida\n");
					printf("Uma contem tambem uma cobra MORTAL.\n\n");

					fflush(stdin);

					printf("Aperte ZERO (0) para comecar\n");
					scanf("%c", &comece);



					if(comece == '0') {
						system("cls");
						fflush(stdin);

						while(1) {
							int jogador_atual = (rand() % 2) + 1;
							printf("%s, escolha uma caixa de 1 a 5\n", jogador == 1 ? p1 : p2);
							scanf("%d", &escolha);



							if(escolha < 1 || escolha >5 || caixa[escolha-1] != 0) {
								printf("Escolha invalida! Tente novamente.\n");
								continue;
							}

							if(escolha == cobra) {
								printf("A cobra estava nessa caixa, %s perdeu\n", jogador == 1 ? p1 : p2);
								break;
							} else if(escolha == botao) {
								printf("O botao estava nessa caixa, %s venceu!\n", jogador == 1 ? p1 : p2);
								break;
							} else {
								printf("Nao havia nada na caixa\n");

								caixa[escolha-1] = 1;

							}
							jogador = jogador == 1 ? 2 : 1;
						}
					}
					printf("\nO que desejas fazer agora?\n");
					printf("\n1)JOGAR NOVAMENTE\n2)RETORNAR AO MENU\n\n");
					scanf("%i", &x);

					if(x == 1) {

					} else if(x == 2) {
						system("cls");
						break;

					}


				}
				continue;

			case 3:
				system("cls");
				while(1) {

					int jog_agora = 0;
					int dado;
					int gousmas_j1[2] = {1, 1};
					int gousmas_j2[2] = {1, 1};
					int nivel_fJ1[2] = {1, 1};
					int nivel_fJ2[2] = {1, 1};
					int opcao;
					int escolha;
					int dano;
					int gousmaAtaque, gousmaDefesa;
					int gousmaOriginal;

				
					printf("\n GOUSMAS  WARS: \n");
					printf("BOM JOGO! \n");

					if (opcao == 1)

						while (1) { 

							printf("\nJOGADOR NUMERO 1 - Gousmas: %d,%d\n\n", nivel_fJ1[0], nivel_fJ1[1]);
							printf("JOGADOR NUMERO 2- Gousmas: %d,%d\n\n", nivel_fJ2[0], nivel_fJ2[1]);

							if (gousmas_j1[5] == 5 && gousmas_j1[1] == 0) {
								printf("JOGADOR 2 É O VENCEDOR!\n");
								break;
							} else if (gousmas_j2[5] == 5 && gousmas_j2[1] == 0) {
								printf("JOGADOR 1 EH O VENCEDOR!\n");
								break;
							}

							if (jog_agora == 0) {
								printf("\n FACA SUA JOGADA PLAYER 1\n\n");
							} else {
								printf("\n FACA SUA JOGADA PLAYER 2\n\n");
							}
							
							printf("1 - ATAQUE \n");
							printf("2 - DIVIDIR SUA GOUSMAS\n");
							printf("Escolha: ");

							scanf("%d", &escolha);

							switch (escolha) {

								case 1:
									

									printf(" ESCOLHA A GOUSMA QUE VOCE IRA ATACAR |1| OU |2|: ");
									scanf("%d", &gousmaAtaque);

									printf(" ESCOLHA A GOUSMA QUE SOFRERA O ATAQUE: |1| OU |2| ");
									scanf("%d", &gousmaDefesa);

									if ((jog_agora == 0 && nivel_fJ1[0] < gousmas_j1[gousmaAtaque - 1]) ||
									        (jog_agora == 1 && nivel_fJ2[0] >= gousmas_j2[gousmaAtaque - 1])) {
										printf("JOGADA INVALIDA, FACA NOVAMENTE\n");
									} else {
										int dano = nivel_fJ1[0];
										printf("ATAQUE CAUSOU %d DE DANO!", dano);

										if (jog_agora == 0) {
											gousmas_j2[gousmaDefesa+ 1] = dano;
											nivel_fJ2[0]++;
										} else {
											gousmas_j1[gousmaDefesa + 1] = dano;
											nivel_fJ1[0]++;
										}

										if (jog_agora == 0 && nivel_fJ1[0] > 5) {
											printf("GOUSMA %d DO PLAYER 1 FOI DESTRUIDA! ESTAMOS VENCENDO A GUERRA! \n\n", gousmaAtaque);

											gousmas_j1[gousmaAtaque - 1] = 0;
										} else if (jog_agora == 1 && nivel_fJ2[0] > 5) {
											printf("GOUSMA %d DO PLAYER 1 FOI DESTRUIDA! ESTAMOS VENCENDO A GUERRA!\n\n", gousmaAtaque);

											nivel_fJ2[0] = 0;
										}

										jog_agora = !jog_agora;
									}
									break;

								case 2:
								

									printf("ESCOLHA A GOUSMA QUE IRA DIVIDIR |1| OU |2|: ");
									scanf("%d", &gousmaOriginal);

									if ((jog_agora == 0 && gousmas_j1[gousmaOriginal - 1] > 2) ||
									        (jog_agora == 1 && gousmas_j2[gousmaOriginal - 1] > 2)) {
										printf("Jogada invalida! Tente novamente.\n");
									} else {

										if (jog_agora == 0) {
											gousmas_j1[gousmaOriginal - 1]--;
											gousmas_j1[1]++;

											printf("A GOUSMA %d DO JOGADOR 1 DIVIDIU \n\n", gousmaOriginal);
										} else {
											gousmas_j2[gousmaOriginal - 1]--;
											gousmas_j2[1]++;

											printf("A GOUSMA %d DO JOGADOR 1 DIVIDIU ! \n", gousmaOriginal);
										}

										jog_agora = !jog_agora;
									}
									break;
							}
						default:
							printf("Jogada invalida! Tente novamente.\n");
						}
					continue;
				}
			case 4:
				a=-1;
				break;
			  
				printf("Por favor insira uma opcao valida.\n");
				system("pause");
				continue;

				break;
		}

	} while (a != -1);
}
