# Design-patterns

Projeto feito com a utilização do padrão de projetos design patterns.

- Strategy é um padrão de design comportamental que permite definir uma família de algoritmos, colocar cada um deles em uma classe separada e tornar seus objetos intercambiáveis. 
  - O padrão Strategy utilizado nesse código visa resolver problemas com a existência de diversos algoritmos para uma ação, resultando na possibilidade de vários if's. 

- Chain of Responsibility é um padrão de design comportamental que permite passar solicitações ao longo de uma cadeia de manipuladores. Ao receber uma solicitação, cada manipulador decide processar a solicitação ou passá-la para o próximo manipulador da cadeia.
  - O padrão Chain of Responsibility é utilizado nesse código para evitar classes com diversas informações jogadas, deixando-as visulamente "poluidas" e dificultando o seu entendimento. Diferentemente do Strategy, nesse padrão utizados atributos não exatos, podendo varias de acordo com as informações inseridas pelo usuário.

- O Template Method é um padrão de design comportamental que define o esqueleto de um algoritmo na superclasse, mas permite que as subclasses substituam etapas específicas do algoritmo sem alterar sua estrutura.
  - O padrão Template Method favoreceu o reaproveitamento de códigos comuns entre classes, evitando assim duplicações de códigos.

- O State é um padrão de design comportamental que permite que um objeto altere seu comportamento quando seu estado interno muda. Parece que o objeto mudou de classe.
  - O padrão State, assim como o padrão Strategy, resolve o problema de muitos ifs no código. Porém ele é utilizado principalmente quando se pode mudar o estado do atributo em questão.

- O Command é um padrão de design comportamental que transforma uma solicitação em um objeto autônomo que contém todas as informações sobre a solicitação. Essa transformação permite passar solicitações como argumentos de método, atrasar ou enfileirar a execução de uma solicitação e oferecer suporte a operações reversíveis.
  - O Command utilizado foi necessário para que não precisaríamos duplicar todo este código em vários lugares.
