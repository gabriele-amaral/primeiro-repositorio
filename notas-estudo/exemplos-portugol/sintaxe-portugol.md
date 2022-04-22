# Sintaxe Portugol



### O formato básico do pseudocódigo em Portugol: 

algoritmo < nome > 
				{Area de declaração de variáveis e constantes}
				,
				{Area de procedimentos e funções}
				.
				{Area de comandos}
				inicio

​				fim

##### Comentários delimitados por { }

##### O Portugol prevê quatro tipos de dados: inteiro, real, caractere e lógico (ou booleano). As palavras-chave que os definem são as seguintes (observe que elas não têm acentuação):

* inteiro: define variáveis numéricas do tipo inteiro, ou seja, sem casas decimais;
* real: define variáveis numéricas do tipo real, ou seja, com casas decimais; 
* caractere: define variáveis do tipo caractere; 
* logico: define variáveis do tipo booleano, ou seja, com valor VERDADEIRO ou FALSO. 

##### Operadores Aritméticos

* +, -, *, /, \ (divisão inteira), MOD(resto da divisão inteira) ^ (potenciação)

##### Operadores Relacionais

* =, <, >, <=, >=, <> 

##### Operadores Lógicos

* ou, nao, e, xou 

##### Entrada de Dados

* ler

##### Saída de Dados

* mostrar

##### Estruturas de repetição

enquanto < expressão-lógica > faca <seqüência-de-comandos>
fim-enquanto

para < variável > de < valor-inicial > até < valor-limite > [passo < incremento >  ] faca 
< seqüência-de-comandos >

repita 
	< seqüência-de-comandos >
até < expressão-lógica >  

##### Estruturas de seleção

se < expressão-lógica >
 entao
 < seqüência-de-comandos-1 >
 senao
 < seqüência-de-comandos-2 >
fimse 

##### ou

se < expressão-lógica > 
 entao
 < seqüência-de-comandos-1 >
fimse

##### ou 

caso < expressão-de-seleção > igual a
condicao1
 < seqüência-de-comandos-1 >
condicao2
 < seqüência-de-comandos-2 >
caso contrario
 < seqüência-de-comandos-extra >
fimcaso

#### Link fonte:

[Valete Dourado](https://github.com/ValeteDourado/dio-desafio-projeto-de-repositorio/blob/be1defb0b12d8ee5d7c143d9fa255802912e1c79/Introdu%C3%A7%C3%A3o%20ao%20portugol/Sintaxe%20Portugol.md)



