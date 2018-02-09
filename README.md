/* Scopo: uso delle variabili bool,nei linguaggi di programazione è possibile definire un tipo di variabile dedicata
alla memorizzazione di dati di tipo booleano cioè che memorizzano solo valori VERO o FALSO,true e false 
In c un espressione logica è: Vera(true)    se assume valore diverso da zero  !=0
                              Falsa(false)  se assume valore uguale  a zero   ==0 */

#include <stdio.h>
#include <stdbool.h>  //Grazie a questa libreria si può utilizzare all'interno del programma il tipo di variabile
                      //bool e le parole riservate true e false

main()

{
  //variabili locali alla funzione main
  bool piove;
  //istruzioni della funzione main
  piove=false;    //false significa 0 stessa cosa di scrivere piove==0
  if (piove==1)   //==0,==1       //ragionare ed allenarsi ad usare true o false sostituento ==0 oppure !=0
    printf("apri l'ombrello"); 
  else
    printf("NON aprire l'ombrello");
    
  printf("\n\n");
  system("PAUSE");	
}
