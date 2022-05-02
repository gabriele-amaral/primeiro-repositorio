# CSS 

É uma linguagem de estilo. Uma regra CSS é representada por um seletor ou um grupo de seletores.

> ### ID x Classe 

**ID** - é representado pelo símbolo **#** *(hash)* seguido de um nome para esse ID;

**Classe** - é representada de forma parecida do ID, mas é precedida por um ponto *(**.**)* em vez do hash *(**#**)*;

E a diferença mais importante entre eles é a forma como devem ser usados: o **ID** só pode ser usado **uma vez** em uma página HTML enquanto a **classe** *não tem restrições*.

**Pseudo-classe** - Elementos HTML sofrem alterações causadas pela interação do usuário, como mover o mouse por cima ou clicar nesse elemento.

#### Exemplo:

```
ID ou Classe:hover{

(modificações)

}
```



> ### Box-model

Quando estamos criando o layout de um site, o navegador representa cada elemento HTML  como uma caixa retangular, isso é o box-model. E com CSS nós alteramos a aparência dessa caixa (largura, altura, cor de fundo, etc.). Essa caixa é composta por 4 áreas: o conteúdo, o padding, a borda e a margem.

As margens (margin) são espaçamentos entre elementos; 
As bordas (border) ; 
O padding é um espaçamento entre as bordas e o conteúdo, a diferença para as margens é que declarações de imagem de fundo funcionam nele; 
O conteúdo (content) é o que o seu bloco representa, um texto, uma imagem, um vídeo.