# Victor
Prova
# inclui  < stdio.h >

int  main (){
    int Idade= 0 ;

    printf ( " Digite a idade: " );
    scanf ( " %d " ,&Idade);

    if (Idade> 18 && Idade<= 65 ){
        printf ( " Eleitor obrigatorio \n " );
    }
    else  if (Idade>= 16 && Idade<= 18 || Idade> 65 ){
        printf ( " Eleitor facultativo \n " );
    }
    senão
    {
        printf ( " Nao eleito \n " );
    }

    sistema ( " pausa " );
    retorna  0 ;
}
