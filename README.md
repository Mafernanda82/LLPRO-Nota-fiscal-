# LLPRO-Nota-fiscal-

#include  <stdio.h>
#include  <stdlib.h>
#include  <locale.h>

int main ( )
{
  setlocale (LC_ALL, " Portuguese_Brazil " );
  
  
  char produto1 [ 18 ],produto2 [ 18 ],produto3 [ 18 ], produto4 [ 18 ],  produto5 [ 18 ], produto6 [ 18 ], produto7 [ 18 ], produto8 [ 18 ];
  float valor_1, valor_2, valor_3,valor_4,valor_5,valor_6,valor_7, valor_8;
  int qtd_1,qtd_2,qtd_3,qtd_4, qtd_5,qtd_6,qtd_7,qtd_8;
  int codigo1 = 928,codigo2 = 638,codigo3 = 273,codigo4 = 294,codigo5 = 465,codigo6 = 176,codigo7 = 837,codigo8 = 958; 
  float preco_total; 


  printf(" Programa pra gerar nota fiscal \n \n");

  printf("\nnome do produto 1: ");
  gets(produto1);
  printf("valor do produto 1: ");
  scanf("%f", & valor_1);
  printf("quantidade do produto 1: ");
  scanf("%d", & qtd_1);
  fflush(stdin);
  
  printf("\nnome do produto 2: ");
  gets(produto2);
  printf("\nvalor do produto 2: ");
  scanf("%f", & valor_2);
  scanf("quantidade do produto 2: ");
  printf("%d", & qtd_2);
  fflush(stdin);
  
  printf("\n nome do produto 3: ");
  gets(produto3);
  printf("valor do produto 3: ");
  scanf("%f", & valor_3);
  scanf("quantidade do produto 3: ");
  printf("%d", & qtd_3);
  fflush(stdin);
  
  printf("\n nome do produto 4: ");
  gets(produto4);
  printf("valor do produto 4: ");
  scanf("%f", & valor_4);
  scanf("quantidade do produto 4: ");
  printf("%d", & qtd_4);
  fflush(stdin);
  
  printf("\n nome do produto 5: ");
  gets(produto5);
  printf("valor do produto 5: ");
  scanf("%f", & valor_5);
  printf("quantidade do produto 5: ");
  scanf("%d", & qtd_5);
  fflush(stdin);
  
  printf("\n nome do produto 6: ");  
  gets(produto6);  
  printf("valor do produto 6: ");  
  scanf("%f", & valor_6);
  printf("quantidade do produto 6: ");
  scanf("%d", & qtd_6);  
  fflush(stdin);

  
  printf("\n nome do produto 7: ");
  gets(produto7);  
  printf("valor do produto 7: ");  
  scanf("%f", & valor_7); 
  printf("quantidade do produto 7: ");
  scanf("%d", & qtd_7);  
  fflush(stdin);

  printf("\n nome do produto 8: ");  
  gets(produto8);  
  printf("valor do produto 8: ");  
  scanf("%f", & valor_8);  
  printf("quantidade do produto 8:");
  scanf("%d", & qtd_8);  
  fflush(stdin);
  
  preco_total = valor_1 * qtd_1 + valor_2 * qtd_2 + valor_3 * qtd_3 + valor_4 *qtd_4 + valor_5 * qtd_5 + valor_6 * qtd_6 + valor_7 * qtd_7 + valor_8 * qtd_8;  

  system("cls");   
  
  
  printf("%-7s| %-7s| %-15s |%-15s| %-15s\n","Codigo", "Quantidade", "Discriminacao", "Preco Unitario", "Preco Total");
  printf("%-7d| %-7d| %-15s |R$ %-12.2f |R$ %-12.2f|\n", codigo1, qtd_1, produto1, valor_1, valor_1*qtd_1);  
  printf("%-7d| %-7d| %-15s |R$ %-12.2f |R$ %-12.2f|\n", codigo2, qtd_2, produto2, valor_2, valor_2*qtd_2); 
  printf("%-7d| %-7d| %-15s |R$ %-12.2f |R$ %-12.2f|\n", codigo3, qtd_3, produto3, valor_3, valor_3*qtd_3); 
  printf("%-7d| %-7d| %-15s |R$ %-12.2f |R$ %-12.2f|\n", codigo4, qtd_4, produto4, valor_4, valor_4*qtd_4);  
  printf("%-7d| %-7d| %-15s |R$ %-12.2f |R$ %-12.2f|\n", codigo5, qtd_5, produto5, valor_5, valor_5*qtd_5);
  printf("%-7d| %-7d| %-15s |R$ %-12.2f |R$ %-12.2f|\n", codigo6, qtd_6, produto6, valor_6, valor_6*qtd_6); 
  printf("%-7d| %-7d| %-15s |R$ %-12.2f |R$ %-12.2f|\n", codigo7, qtd_7, produto7, valor_7, valor_7*qtd_7);  
  printf("%-7d|%-7d | %-15s |R$ %-12.2f |R$ %-12.2f|\n", codigo8, qtd_8, produto8, valor_8, valor_8*qtd_8); 
  printf("%-7s| %-7s| %-15s |%-15s |R$ %-15f\n", "", "", "", "Total",preco_total);  
  
  system("pause");

    return 0 ;                                                                                                                                                                                                                                                                                                                    
                                                                                                                                                                                                                  
}                                                                                                                        


