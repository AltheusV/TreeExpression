<a href="README-PTBR.md">
<img src="https://user-images.githubusercontent.com/30200769/116628303-33085400-a925-11eb-85d7-9bbcf3b1a791.png" width="30" alt="pt-br">
<a/>

<a href="README.md">
<img src="https://user-images.githubusercontent.com/30200769/116637950-9b623000-a93b-11eb-9eed-06f587750c48.png" width="30" alt="eng-us">
<a/>

 # TreeExpression
  
 TreeExpression is an algorithm that I made when I was learning about data structures. It is built wih the concepts of a binary expression tree and a stack data structure.
 
 The algorithm creates a tree of an entered numeric expression and calculates its result.
  
 In order to use properly, you must attent to the following correct and incorrect formats examples:
  
  ## Incorrect Format:
  (a+b)
  
  ( + )
  
  ( ( a * 2 ) ( 2 / a ) )
  
  ) a + b (
  
  2 * ( a + b )
  
  ## Correct Format:
  
 ( a + b )
  
 ( ( ( 2 * 4 ) / ( a * b ) ) / ( 3 * c ) )
  
 ( ( b * b ) - ( ( 4 * a ) * c ) )
  
 ( ( ( ( ( a + b ) + c ) * d ) / ( a - b ) ) + ( ( a * b ) - ( a * d ) ) )
  
 ( ( ( 2 * 4 ) + ( ( 3 - 4 ) * ( 5 + 3 ) ) ) /  ( ( 3 / 4 ) * ( 3 * 4 ) ) )
