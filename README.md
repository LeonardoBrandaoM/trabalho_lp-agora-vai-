# Grupo :
* Leonardo Brandão
* Samuel Galasso

# Funcionalidades :
## Expansão de Includes: 
Processa diretivas '#include' para incorporar conteúdo de arquivos externos.
## Expansão de Defines:
Substitui macros definidas por seus valores correspondentes.
## Remoção de Comentários: 
Remove comentários do tipo // do código.
## Minificação: 
Remove espaços em excesso para reduzir o tamanho do código. Tornando-o em uma unica linha.

# Como Usar

## Compilação :
Salve o código em um arquivo chamado, por exemplo 'programa.c' e utilize o compilador, nesse caso o GCC para compilar, da seguinte forma :
    
    gcc -o programa programa.c

# Execução
Prepare um arquivo de entrada para sofrer o processo, por exemplo, 'entrada.txt' e um arquivo de saida como 'saida.txt' e execute o programa com :

    ./programa entrada.txt saida.txt

## O resultado processado será salvo no arquivo 'saida.txt'
# //----------//----------//----------//
# Estrutura do Código:
## DefineEntry: 
Estrutura que representa uma macro com nome, valor e argumentos.
## Funções de Manipulação de Macros:
 Funções que gerenciam a tabela de macros e aplicam substituições.
## Funções de Processamento de Arquivo:
 Funções responsavéis por processar o arquivo de entrada para remoção de comentários e minificação.

