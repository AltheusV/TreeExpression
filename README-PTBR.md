<a href="README-PTBR.md">
<img src="https://user-images.githubusercontent.com/30200769/116628303-33085400-a925-11eb-85d7-9bbcf3b1a791.png" width="30" alt="pt-br">
<a/>

<a href="README.md">
<img src="https://user-images.githubusercontent.com/30200769/116637950-9b623000-a93b-11eb-9eed-06f587750c48.png" width="30" alt="eng-us">
<a/>

  # TreeExpression
  
  TreeExpression é um algoritmo que fiz quando estava aprendendo sobre estruturas de dados. Ele é construído com os conceitos de uma árvore de expressão binária e uma estrutura  de pilha de dados.
  
  O algoritmo cria uma árvore de uma expressão numérica inserida e calcula seu resultado.
  
  Para usar corretamente, você deve prestar atenção aos seguintes exemplos de formatos corretos e incorretos:
  
  ## Formato Incorreto:
  (a+b)
  
  ( + )
  
  ( ( a * 2 ) ( 2 / a ) )
  
  ) a + b (
  
  2 * ( a + b )
  
  ## Formato Correto:
  
 ( a + b )
  
 ( ( ( 2 * 4 ) / ( a * b ) ) / ( 3 * c ) )
  
 ( ( b * b ) - ( ( 4 * a ) * c ) )
  
 ( ( ( ( ( a + b ) + c ) * d ) / ( a - b ) ) + ( ( a * b ) - ( a * d ) ) )
  
 ( ( ( 2 * 4 ) + ( ( 3 - 4 ) * ( 5 + 3 ) ) ) /  ( ( 3 / 4 ) * ( 3 * 4 ) ) )
