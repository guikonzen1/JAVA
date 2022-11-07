# JAVA ☕
Repositório para anotações das aulas e cursos de JAVA!
## Variáveis e Tipos básicos em Java 
<li>Sintaxe : (tipo) (nome) = (valor inicial) <--(opcional)

Tipos de variáveis:

![image1](https://user-images.githubusercontent.com/108848546/200203881-d9d7fdc0-60cb-4d56-81a5-ad7ceba7e04d.png)

Há também a variável String - que é uma cadeia de caracteres (palavras ou textos).

# Saída de dados (print)
Há duas formas de printar o código na tela, um com quebra de linha e outra sem:
Sem quebra de Linha: System.out.print("Bom dia!")
Com quebra de Linha: System.out.println("Bom dia!")

Para limitar o número de casas decimais quando utilizar uma variável com número flutuante se utiliza este metódo:
x = 10.35784
System.out.printf("%.2f%n", x) <--nesse caso utiliza-se o 2f para ser o limitante, irá mostrar somente duas casas decimais, o %n é a quebra de linha, já que para limitar a casa decimal se utiliza o printf (nesse caso ele irá arredondar), para mostrar com 4 casas basta alterar o 2 para 4.

Para concatenar vários elementos em um mesmo print ou prinln usa-se esse metódo:

System.out.println("RESULTADO = " + x + "METROS")

Para concatenar um elemento em um printf usa-se esse metódo:

System.out.printf("RESULTADO = %.2f METROS%n", x) <-- O ponto flutuante deve ser colocado onde o valor da variável tem de ser concatenado

Para concatenar vários elementos em um printf usa-se esse metódo:

System.out.printf("%s tem %d anos e ganha R$ %.2f reais%n", nome, idade, renda);

onde:
<table> <td>%f = ponto flutuante</td> <td>%d = inteiro</td> <td>%s = texto</td><td> %n = quebra de linha</td>
