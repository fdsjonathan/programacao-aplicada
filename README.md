# Programação Aplicada

# Aula 01 - Introdução da Disciplina

# Aula 02 - Introdução da Linguagem C.
1. Sintaxe Linguagem Phyton:
   * No phyton temos que cuidar a identação.

2. Sintaxe Linguagem C:
   * No C não precisamos cuidar a identação, pois ele ignoras os espaços em branco, mas se utiliza para melhor visualizaçao do código.

3. Comparação entre linguagem phyton e C:
   Ambas as linguagens podem ser programadas sem o uso de uma IDE.
   No phyton podemos escrever o código no bloco de notas e salvar um arquivo .py, após rodar no CMD.
   No C também podemos escrever o código no bloco de notas e salvar um arquvo .c, apos copilar e executar no CMD.

4. Saída em C:
   " " -
   \n -
   \t -
   \\ -
   \" -
   
5. Exercício:
 int main() {
  printf("| Seg |  Terça   |   Quarta  |\n");
  printf("| BD1 | Fisica 1 | Calculo 1 |\n");
  printf("Mas a \"Melhor\" disciplina \né \\Programação Aplicada\\");
  return 0;
}

# Aula 03 - Iniciando a aprendizagem da Linguagem C.
Objetivo: Entrada e Saida de Dados / Tipos de dados primitivos.

Praticas em Aula: https://replit.com/

#include <stdio.h>

int main(void) {
  char nomePessoa[10];
  int idade;
  float nota1;
  float nota2;
  float nota3;
  float media;
  int numero;

  // Exercício 01
  
  printf("Hello World\n"); //Função de Saida de Dados. \n adiciona nova linha.
  printf("Iniciando a aprendizagem da Linguagem C. \n");
  /*
  printf("Qual seu nome?\n");
  scanf("%s",nomePessoa);
  printf("Seja bem vindo %s\n",nomePessoa);
  //printf("Qual a sua idade? \n");
  //scanf("%i",&idade);
  //printf("O dobro da sua idade é de: %i\n",2*idade);

  //printf("Digite a primeira nota\n");
  //scanf("%f",&nota1);
  //printf("Digite a segunda nota\n");
  //scanf("%f",&nota2);
  //printf("Digite a terceira nota\n");
  //scanf("%f",&nota3);
  //media = (nota1+nota2+nota3)/3;
  //printf("A média das suas notas é: %f\n",media);

  /*
  printf("Digite um número\n");
  scanf("%i", &numero);
  printf("O número antecessor do número digitado é: %i\n",numero-1);
  printf("O número sucessor do número digitado é: %i\n",numero+1);

  /*
    A linguagem C posssui 4 tipos de dados primitivos.
    Cada um armazena um tipo de informação e possui um tamanho diferente em bytes.

    char    1 byte    Armazena caracteres.
    int     4 bytes   Armazena números inteiros.
    float   4 bytes   Armazana números reais até 6 casas decimais.
    double  8 bytes   Armazena números reais até 15 casas decimais.

  */

  char minhaLetra = 'j';
  int copaBrasil = 1991;
  float floatPi = 3.14159265359;
  double doublePi = 3.14159265359;

  printf("\nCaracter:      %c                  Tamanho: %lu byte(s)\n", minhaLetra, sizeof(minhaLetra));
  printf("Valor int:     %i               Tamanho: %lu byte(s)\n", copaBrasil, sizeof(copaBrasil));
  printf("Valor float:   %f           Tamanho: %lu byte(s)\n", floatPi, sizeof(floatPi));
  printf("Valor double:  %.15f  Tamanho: %lu byte(s)\n", doublePi, sizeof(doublePi));

  /*
  A linguagem C possui 4 tipos de modificadores de tipo.
  Estes modificadores definem um novo tamanho ou sinal para as variáveis.

  short    Divide na metade o tamanho de uma variável.
  long     Dobra o tamnho de uma variável.
  signed   Define como númeors apenas positivos
  unsigned Define como números positivos e negativos.
  */
   return 0;
}
