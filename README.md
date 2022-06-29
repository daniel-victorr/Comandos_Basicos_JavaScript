

# Comandos básicos de JavaScript para iniciantes
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Tipos de dados 


 1. Number      
  
    1.1 infinity   
    1.2 NaN         

 2. boolean     

 3. null        

 4. undefined   

 5. function   
  
 6. String     

 7.  object      

 8.  Array     

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Declarações de variáveis
                                      

  var $nome = 'Daniel'
 
  var $segundo_nome = "Victor"
 
  var _nome = 'Daniel'
 
  var nome = 'Daniel';  
 
  var nome = "Daniel"
 
  nome = 'Daniel'                  
 
  var salario = 10
   
 -------- Ou ---------
 
  let nome = 'Daniel'; 
 
  let nome = "Daniel"
 
  let $nome = 'Daniel'
 
  $nome = 'Daniel'
 
  let _nome = 'Daniel'
 
  nome = 'Daniel'
  
  let $segundo_nome = "Victor"
  
  nome = 'Daniel'
  
  var salario = 10.99 

  exemplo de atribuição com função:
 
  nome = window.alert()  
  <br>
  * <Strong>OBS:</Strong> Podemos usar acentos ou símbolos como por exemplo: var vírgula = ',' 
  
  * <Strong>NÃO</Strong> podemos deixar espaços em branco como por exemplo: var nome sobrenome
   
  * <Strong>NÃO</Strong> podemos começar com número como por exemplo: 1nome 
   
  * <Strong>NÃO</Strong> podemos utilizar palavras reservadas como por exemplo: var let = 10
   
  * <ins>Maiúsculas</ins> e <ins>Minúsculas</ins> fazem diferença.
                                           
  <br>
   Podemos atribuir valores inteiros e reais para as nossas variávies.
  
   Podemos atribuir função.
   
   Podemos atribuir objto.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## typeof  

<em>typeof -> mostra a tipagem das variável ou dados.</em>
 
   var n = 100
 
   typeof n
   'number'

   typeof 6 
   'number'

   typeof 'Google'
   'string'
 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Eventos 

  window.alert()    mostra uma janela com  as imformações  e também com o botão: ok.
  
  window.prompt()   mostra uma janela para o usuário digitar e também com o botões ok.
  
  window.confirm()  mostra uma janela com o botão: ok.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Comentários 
 
  /* comentário de várias linhas
    text
    text
    text
    text
  */ 

  // comentário de uma única linha

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Converção de dados:

  n1 = Number(window.prompt('Informe um número')
 
  n2 = 10.90
 
  soma = n1 + n2;
  
  window.alert('O valor da soma é: ' + soma.toFixed(2)) <em> ->  Essa linha faz o nosso valor ficar com duas casas depois do ponto.</em>  
  
  Number.parseInt(n1)
  
  Number.parseFloat(n1)
  
  String(n2)
  
  n2.toString()
  
  
  <strong>OBS:</strong> podemos colocar a quantidade que desejarmos dentro dos parênteses.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


