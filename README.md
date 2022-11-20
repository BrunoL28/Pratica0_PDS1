# PrAtica_1_PDS1

Exercício 0: Alô mundo!
O programa abaixo é o primeiro programa que você vai fazer na linguagem C. 
É um programa que simplesmente imprime “Alo mundo!” na tela. 
Digite o programa abaixo no seu editor de programas favorito. Depois, compile e execute o programa.


    #include <stdio.h>
    int main(){
    
    printf(“Alo mundo!”);
    return 0;
    }

Exercício 1: Impressão do nome

Escreva um programa que imprime o seu nome completo na tela.

Exercício 2: Sinal sonoro

Escreva um programa que emite um sinal sonoro. Para isso, basta imprimir o caractere especial ‘\a‘, ou seja, ao invés de imprimir “Alo mundo” ou o seu nome, imprima esse caractere especial.

Exercício 3: Cálculo do Seno de 3,14 e de 4,13

Escreva um programa que imprime na tela os senos de 3,14 e de 4,13. Use (= copiar e colar) o código que imprime o seno de 1,5, que está nos slides da Aula 2, para auxiliá-lo. E não se preocupe, boa parte desse código é novidade para você! No entanto, mão é muito difícil deduzir quais operações você precisa alterar (e criar) para imprimir os valores dos senos pedidos nesta questão.

Exercício 4: Impressão dos arquivos da pasta

Escreva um programa que imprime na tela todos os arquivos da pasta. Para isso, chame a operação system(“dir”) (ou system(“ls”), no Linux). A função “system” da linguagem C (biblioteca “stdlib.h”) executa uma operação do sistema operacional e o comando “dir” do prompt de comando (ou “ls”, se está em um sistema UNIX) lista os arquivos da pasta.
