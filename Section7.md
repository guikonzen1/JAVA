# Outros tópicos básicos em JAVA

## Convenções na escrita:
Cammel Case: lastName
é usado em: atributos, pacotes, metódos, variáveis e parametros 

PascalCase: FistESecondName
é usado em: classes

## Operador Bitwise (XOR)
É declarado com: ^
O xor só é verdadeiro quando uma das condições é verdadeira, caso ambas sejam verdadeiras a saída será falsa.

uma aplicação comum do XOR é a verificação de bit, isso pode ser verificado no seguinte código:

![image](https://user-images.githubusercontent.com/108848546/202769115-a3853904-df52-4aa3-8af8-d8e590275af5.png)

detalhe que nesse código da para perceber que o valor definido para a variável mak está em binário, sendo assim possível definir valores binários após, para fazer isso basta colocar <b>0b</b> e depois o valor do número em binário, nesse caso: 0b00100000 onde equivale a 32, os zeros do lado esquerdo do número 1 são ignorados, podendo escrever assim: 0b100000


## Funções para STRING

<body>
<ul>
<li>Formatar: toLowerCase(), toUpperCase(), trim()</li>
<li>Recortar: substring(inicio), substring(inicio, fim)</li>
<li>Substituir: Replace(char, char), Replace(string, string)</li>
<li>Buscar: IndexOf, LastIndexOf</li>
</ul>
</body>

Para verificar o que cada um faz e como funcionam basta visualizar nesse <a href="https://github.com/guikonzen1/JAVA/blob/main/StringFunctionEX.java">código.</a> 

<li>str.Split(" ")</li> já o split funciona diferente das outras, essa função pega os valores separados por um espaço dentro de uma string e o transforma em variáveis colocando dentro de vetores cada valor.





