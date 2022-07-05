# Design-patterns

Projeto feito com a utilização do padrão de projetos design patterns.

- Strategy é um padrão de design comportamental que permite definir uma família de algoritmos, colocar cada um deles em uma classe separada e tornar seus objetos intercambiáveis. 
  - O padrão Strategy utilizado nesse código visa resolver problemas com a existência de diversos algoritmos para uma ação, resultando na possibilidade de vários if's. 

- Chain of Responsibility é um padrão de design comportamental que permite passar solicitações ao longo de uma cadeia de manipuladores. Ao receber uma solicitação, cada manipulador decide processar a solicitação ou passá-la para o próximo manipulador da cadeia.
  - O padrão Chain of Responsibility é utilizado nesse código para evitar classes com diversas informações jogadas, deixando-as visulamente "poluidas" e dificultando o seu entendimento. Diferentemente do Strategy, nesse padrão utizados atributos não exatos, podendo varias de acordo com as informações inseridas pelo usuário.
