/*
 *nom : Benoit.Phan
 *date : 06/11/2024
 *exercice: Construire des programme multipliant et divisant sna utliser le *
 */
#include <stdio.h>
int main () {
 int question ;
 int nb1 ;
 int nb2 ;
 int rest  ;
 int lol ;

 printf("Veux tu faire une multiplication si oui tape 1 , si non tape 2  :");
 scanf("%d" , &question );
 printf("donne le premier chiffre  :");
 scanf("%d" , &nb1);
 printf("donne le deuxième chiffre  :");
 scanf("%d" , &nb2);
 if (question == 1) {
  rest=0 ;
  for (;nb1>0 ;nb1-- ) {
   rest = rest + nb2 ;
  }
  }else {
   rest = nb1  ;
   for (;rest>=nb2 ;) {
    rest = rest - nb2 ;
    lol = rest;

   }
  }
 printf("%d" , lol);
 }
