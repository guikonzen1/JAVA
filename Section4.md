# AULA 1 ☕
Repositório para anotações das aulas e cursos de JAVA!
## Variáveis e Tipos básicos em Java 
<li>Sintaxe : (tipo) (nome) = (valor inicial) <--(opcional)

Tipos de variáveis:

![image1](https://user-images.githubusercontent.com/108848546/200203881-d9d7fdc0-60cb-4d56-81a5-ad7ceba7e04d.png)

Há também a variável String - que é uma cadeia de caracteres (palavras ou textos).

## Saída de dados (print)
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
<table> <td>%f = ponto flutuante</td> <td>%d = inteiro</td> <td>%s = texto</td><td> %n = quebra de linha</td></table>


## Entrada de dados
Para utilizar a entrada de dados no Java é necessário importar a biblioteca java.util.Scanner, após importar, é necessário indicar para o compilador que você vai utilizar o teclado do usuário para dar entrada de dados dentro do código, para fazer isso realize esses passos:

Na primeira parte do código colocar: Scanner sc = new Scanner(System.in);

e no final do código: sc.close();

esses passos são necessários para que o compilador identifique que você vai utilizar a entrada de dados, agora precisa indicar no código quando ira utilizar essa entrada de dados, para fazer isso basta realizar os seguintes passos:

String x;

x = sc.next(); <-- esse comando irá permitir que escreva uma palavra e essa palavra será armazenada dentro da variável x.

A função sc.next() funciona apenas com a variável de tipo string, caso for alocado uma variável de outro tipo tem que adaptar o comando, como nesses exemplos:

int x;

x = sc.nextInt(); 

caso double: 

x = sc.nextDouble();

para char:

x = sc.next().charAt(0); <--Esse charAt(0) implica que obrigatóriamente o primeiro valor digitado sejá atribuido a x (mesmo que seja digitado mais de uma letra, para mudar qual letra irá atribuir basta mudar o valor de 0 para a posição desejada) 


### Para ler um texto até a quebra de linha
Para ler um texto até a quebra de linha (até dar enter) basta utilizar essa função:

sc.nextLine();

Isso utíl para quando precisar dar entrada em multiplas palavras, caso não use essa função quando digitar e dar o espaço o compilador irá identificar como outra palavra, e não uma igual.

Quando você usa um comando de leitura diferente do nextLine() e da alguma quebra de linha, essa quebra de linha fica "pendente" na entrada padrão, se você fizer um nextLine(), aquela quebra de linha pendente será absorvida pelo próximo nextLine(). Para resolver isso faça um nextLine() extra antes de fazer o nextLine() de seu interesse (EntradadeDadosSCANNER2.java <-- exemplo).

### Funções matematicas básicas em java


![image](https://user-images.githubusercontent.com/108848546/200218669-0187644f-7140-4ce9-9fa5-6076d36e18b3.png)
