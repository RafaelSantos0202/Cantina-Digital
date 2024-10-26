# Documentação do Projeto - Cantina Digital

## Grupo 04
- Rafael Gonçalves dos Santos-33598495
- Vinicius Holtz Mendes Vismara - 4932712740
- Guilherme Cezar Goes - 4933250278
- Vitor da Silva Ribeiro - 32614705
- Keone Keizo Aguilar Oliveira - 4935676116

## Introdução:

Apresentamos a Cantina Digital, o aplicativo ideal para tornar sua experiência na cantina da faculdade mais rápida e eficiente. Com o objetivo de reduzir filas e evitar aglomerações, o Cantina Express permite que você faça seus pedidos diretamente pelo app, de forma prática e conveniente. Basta selecionar os produtos desejados, realizar o pagamento online e aguardar a notificação de que seu pedido está pronto para retirada. Com o Cantina Digital, você economiza tempo, evita filas e aproveita melhor os seus intervalos. Mais agilidade, menos espera, e uma cantina mais organizada!


## Descrição do Produto:

A Cantina Digital é um aplicativo voltado para a otimização do processo de pedidos na cantina da sua faculdade. Através dele, os usuários podem visualizar o cardápio completo, selecionar os itens desejados e realizar o pagamento diretamente no app. Com foco em evitar filas e reduzir o tempo de espera, o Cantina Digital notifica o usuário assim que o pedido estiver pronto para ser retirado, permitindo que ele vá à cantina apenas para buscar seu produto, evitando aglomerações. O app oferece uma interface simples, intuitiva e segura, proporcionando uma experiência mais rápida e eficiente no dia a dia acadêmico

## Etapas de Desenvolvimento 
- 1 -	Esboço do App
- 2 -	Definir padrão do Layout do App
- 3 -	Pagina de cadastro
- 4 -	Desenvolvimento do código
- 5 -	Cadastro do cardápio 
- 6 -	Testes e verificações
- 7 -	Aperfeiçoamento 




## Requisitos Iniciais

- 1 - Cadastro de Usuario: Os usuários inserem suas informações para um cadastro padrão.

- 2 - Metodo de pagamento: O aplicativo deve permitir que os usuários tenha diferentes opções para o métodos de pagamento.

- 3 - Menu do Cardapio: Os usuários deve ter acesso completo ao cardapio da cantina
  
- 4 - Notificações: O aplicativo deve enviar notificações para informar ao usuario se seu pedido está pronto para retirada.

## Metodologia de Desenvolvimento:

O projeto será desenvolvido seguindo a metodologia ágil SCRUM. O SCRUM foi escolhido devido à sua capacidade de adaptar-se a mudanças de requisitos, prioridades e circunstâncias durante o desenvolvimento do projeto, o que é essencial em um contexto de desenvolvimento de software. O trabalho será dividido em sprints de curto prazo, com entregas incrementais e iterativas do produto, permitindo feedback rápido e adaptação contínua. 

## Tecnologias Utilizadas:

### Para o desenvolvimento do aplicativo, serão utilizadas as seguintes tecnologias:

- Node.js: Será utilizado como ambiente de execução para o servidor do aplicativo. Node.js permite a construção de aplicativos escaláveis e de alto desempenho com JavaScript do lado do servidor.

- JavaScript (Frontend): Para o desenvolvimento da interface do usuário do aplicativo, será utilizado JavaScript juntamente com HTML e CSS. Essas tecnologias permitem a criação de interfaces interativas e responsivas, fundamentais para garantir uma experiência de usuário positiva.

- Framework para Aplicativos Móveis: Para a versão móvel do aplicativo, será utilizado um framework adequado para o desenvolvimento multiplataforma. Opções como React Native ou Flutter serão consideradas, permitindo o desenvolvimento de aplicativos nativos para Android e iOS utilizando uma única base de código.

- Banco de Dados: Para armazenar as informações dos usuários e dos medicamentos, será utilizado um banco de dados relacional ou NoSQL, dependendo das necessidades específicas do projeto. Opções como MongoDB, MySQL ou PostgreSQL serão consideradas, levando em conta requisitos de escalabilidade, desempenho e facilidade de uso.

## Design Patterns Utilizados:

### Para o desenvolvimento do aplicativo, serão ultilizadas os seguintes designs patterns:

### Padrões Estruturais:

- Facade: Facilita o acesso às funcionalidades principais, como cadastro, visualização do cardápio e pagamento, escondendo a complexidade do sistema. Um Facade unificado permite que os usuários interajam com o app sem lidar com os detalhes internos de cada módulo.

- Decorator: Este padrão pode ser aplicado para adicionar funcionalidades a produtos específicos do menu. Por exemplo, uma bebida pode ser personalizada com adicionais como gelo, cobertura extra ou sabores extras, sem a necessidade de modificar as classes de bebidas originais.

### Padrões Criacionais:

- Factory Method: Usado para criar diferentes tipos de pedidos no app, como pedido de lanches, bebidas ou produtos específicos, sem especificar as classes concretas. Isso permite que o aplicativo gerencie múltiplos tipos de pedidos com uma única interface, facilitando a adição de novos tipos no futuro.

- Builder: Útil para construir pedidos complexos, como um combo personalizado com lanche, bebida e sobremesa. O padrão Builder pode ajudar a criar diferentes tipos de pedidos passo a passo, tornando o código mais organizado e o processo de montagem do pedido mais flexível. 

### Padrões Comportamentais:

- Observer: Ideal para implementar o sistema de notificações. Quando um pedido é atualizado no servidor, o app pode notificar automaticamente o usuário assim que o pedido estiver pronto, mantendo-o informado em tempo real.

- Command: Cada ação do usuário, como criar um pedido, adicionar itens ao carrinho ou confirmar um pagamento, pode ser encapsulada como um Command, o que permite gerenciar, desfazer ou agendar comandos de forma mais organizada e flexível.

## Conclusão:

A Cantina Digital surge como uma solução inovadora para modernizar e agilizar o processo de pedidos na cantina da faculdade. Com um design intuitivo, funcionalidades práticas e o uso de uma metodologia de desenvolvimento ágil, o aplicativo irá transformar a maneira como estudantes e funcionários interagem com a cantina, oferecendo conveniência, rapidez e evitando aglomerações.
