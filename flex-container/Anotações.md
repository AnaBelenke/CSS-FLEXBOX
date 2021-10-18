## Flexbox em CSS 

-> Flex container 

#DISPLAY:FLEX; 
-> MANIPULAÇÃO DE ITENS

#FLEX-DIRECTION; 
-> EIXO PRINCIPA - DEFINE COMPORTAMENTO DE LINHA E COLUNA 

#ROW->DIREÇÃO 
  ESQUEDA PARA DIREITA 
  --------------------------->

#ROW-RESEVERSE->DIREÇÃO 
  ESQUEDA PARA DIREITA 
  <---------------------------

#COLUMN
  CIMA PARA BAIXO

#COLUMN-RESEVERSE 
  BAIXO PARA CIMA 

________________________________________________________________________

##FLEX WRAP 
-> QUEBRA DE LINHA 
*EVITAR VAZAMENTO DE ITENS* 

#NOWRAP -> PADRÃO 
-> NÃO QUEBRA DE LINHA 
 
#WRAP   
-> PERMITE A QUEBRA DE LINHA 
 
#WRAP-REVERSE  
-> ADICIONA ITEM NA LINHA ACIMA 

________________________________________________________________________

##FLEX-FLOW 
-> ATALHO 
	-> FLEX-WRAP
	->FLEX-DIRECTION 

________________________________________________________________________

##JUSTIFY CONTENT 
 -> ALINHA OS ITENS DO CONTAINER COM DIREÇÃO E DISTRIBUIÇÃO DE ESPAÇO 

#FLEX-START 
-> INICIO DO CONTAINER 

#FLEX-END 
-> FINAL DO CONTAINER 

#CENTER 
-> AO CENTRO DO CONTAINER

#SPACE-BETWEEN 
-> ESPAÇO IGUAL ENTRE ITENS

#SPACE-AROUND 
->ESPAÇOS MAIORES NO MEIO E MENORES NO FINAL  
 
 ________________________________________________________________________

 ##ALIGN-ITEMS

 -> ALINHAMENTO DE ACORDO COM O EIXO 
 ->ALINHA DIFERENTE 
 -> ALINHA CENTRAL EIXO VERTICAL 

 #CENTER 
 -> ALINHA CENTRO (VAI CRESCER DE ACORDO COM TEXTO)

 #STRETCH  
 -> PADRÃO (ITEMS CRESCEM IGUAIS)

 #FLEX-START
 -> ALINHA INICIO (SE MANTEM NA LINHA DE ACIMA)

 #FLEX-END
 -> ALINHA FINAL (SE MANTEM NA LINHA DE ABAIXO)

 #BASELINE 
 -> ALINHA DE ACORDO COM A LINHA BASE DA TIPOGRAFIA DOS ITENS 

________________________________________________________________________


 ##ALIGN-CONTENT

 -> ALINHAMENTO DAS LINHA EM RELAÇÃO AO EIXO VERTICAL 
 REGRAS 
 ->UTILIZE QUEBRA DE LINHA
 ->ALTURA MAIOR QUE SOMA DAS LINHAS 

 #CENTER  

 #STRETCH  
 
 #FLEX-START
 
 #FLEX-END
 
 #BASELINE 
 
________________________________________________________________________



