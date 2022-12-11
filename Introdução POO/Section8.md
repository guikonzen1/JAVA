# Introdução a POO

Esse código foi escrito sem utilizar POO: 

![image](https://user-images.githubusercontent.com/108848546/206021630-5f45979f-9bfb-4796-91c2-761a13e7c686.png)

Porém esse código traz um problema, Triângulo é uma entidade com três atributos: a, b e c. Estamos usando três variáveis para representar cada triângulo: doubel aX, bX, cX, aY, bY, cY;

para melhorar isso, vamos usar uma <b>CLASSE<b/> para representar um triângulo.
##
## Classe
  
<body>
<ul>É um tipo estruturado que pode conter (membros):
<li>Atributos (dados / campos)</li>
  <li>Métodos (funções / operações)</li>
</ul>
</body>
  
<body>
<ul>A classe também pode prover muitos outros recursos, tais como:
<li>Construtores</li>
<li>Sobrecarga</li>
<li>Encapsulamento</li>
<li>Herança</li>
<li>Polimorfismo</li>
</ul>
</body>
  
<body>
<ul>Exemplos:
<li>Entidades: Produto, Cliente, Triangulo</li>
<li>Serviços: ProdutoService, ClienteService, EmailService, StorageService</li>
<li>Controladores: ProdutoController, ClienteController</li>
<li>Utilitários: Calculadora, Compactador</li>
<li>Outros (views, repositórios, gerenciadores, etc.)</li>
</ul>
</body>

 Para criar uma classe utiliza essa sintaxe:
  
  ![image](https://user-images.githubusercontent.com/108848546/206927294-c233d01c-bc05-42dc-a73d-ea688f9c2ae1.png)
  
  Por enquanto essa classe tem somente atributos, mas lembrando que ela pode ter metódos. 
  Fazendo isso, você transforma o Triangle em um tipo de "variável", assim aquele código anterior podera ficar com o inicio bem mais resumido:
  
  ![image](https://user-images.githubusercontent.com/108848546/206927468-9866967c-aea5-4f16-80f9-5ca0b936c47f.png)
  
  Mas como é salvo 2 valores diferentes em uma mesma variável? isso é chamado de alocação dinâmica. As variáveis estaticas ficam armazenadas numa área da memória chamada stack, quando executamos nosso programa ele faz uma alocação dinâmica de memória, isso é, durante a execução do programa será criado um endereço na area heap da memória, essa área é onde é criado os objetos dinâmicos durante a execução do projeto. Nesse caso acima a variável x e y são variáveis estaticas, quando o programa é executado elas apontam pra um local dentro da memóra Heap e nesse endereço tem os 3 valores indicados:
 
  ![image](https://user-images.githubusercontent.com/108848546/206928917-2302aad8-2530-4e22-ab86-a7c59719e86c.png)

  
  
