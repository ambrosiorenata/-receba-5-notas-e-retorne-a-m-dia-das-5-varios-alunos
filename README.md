# -receba-5-notas-e-retorne-a-m-dia-das-5-varios-alunos
#include <stdio.h>
#include <stdio.h>

int main(void)
{
 //Crie um algoritmo que receba 5 notas e retorne a média das 5 
 
int cont;
char cod;

float nota, media, total;

total = 0;

cod = 'C';

while (cod != 'F') {


for (cont = 1; cont <=5; cont++) {
    
 printf("Digite a nota:");
 
  scanf("%f", &nota);
   
   total = total + nota;
   
}

media = total / 5;

printf("Nota media:%.2f\n\n",media);
total = 0;
nota = 0;

printf ("Deseja calcular a media de mais um aluno ? Pressione qualquer tecla para prosseguir, ou a tecla 'F' para finalizar\n");
  
  cod = getchar () ;
  
}

  return 0;
  
}
