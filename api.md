# API

Uma API, ou Interface de Programação de Aplicações, é como um garçom em um restaurante. Você, como cliente (ou aplicação), pede algo ao garçom (API), e o garçom se comunica com a cozinha (sistema ou serviço) para atender ao seu pedido. A API define as regras para fazer pedidos (chamadas) e receber pratos (dados ou funcionalidades) de uma aplicação para outra.

Em termos mais técnicos, uma API permite que diferentes softwares se comuniquem entre si, facilitando a troca de dados e funcionalidades. É como uma ponte que conecta diferentes partes de um sistema ou diferentes sistemas, permitindo que trabalhem juntos de maneira eficiente e harmoniosa.

# Diferença entre REST e RESTful

REST (Representational State Transfer):

É um estilo arquitetural para projetar sistemas distribuídos, frequentemente usado na construção de serviços web.
Baseia-se em princípios como statelessness (ausência de estado) e a manipulação de recursos identificados por URLs.
Utiliza métodos HTTP padrão, como GET, POST, PUT e DELETE, para operações em recursos.

RESTful:

Refere-se a sistemas que seguem os princípios do REST.
Um serviço ou sistema é considerado RESTful se adere às práticas e convenções do REST.
Isso inclui o uso adequado de verbos HTTP, manipulação de recursos via URLs, e a comunicação stateless, onde cada requisição do cliente contém toda a informação necessária.
Em resumo, REST é um estilo arquitetural, enquanto RESTful descreve a implementação prática desse estilo em um sistema específico. Se um sistema é chamado de RESTful, isso significa que ele segue as boas práticas e princípios do REST, proporcionando uma comunicação eficiente e padronizada entre sistemas distribuídos.

# Diferença entre Statelessness e Stateful

**Statelessness (Ausência de Estado):**
  - Em um sistema stateless, cada requisição do cliente para o servidor é tratada de forma independente, sem que o servidor mantenha informações sobre requisições anteriores.
  - Cada requisição do cliente contém todas as informações necessárias para que o servidor compreenda e processe a solicitação.

**Stateful (Com Estado):**
  - Em um sistema stateful, o servidor mantém informações sobre o estado do cliente entre requisições.
  - O servidor armazena dados sobre a interação do cliente para lembrar o contexto e o estado entre requisições sucessivas.

**Comparação Simples:**
  - Stateless é como uma conversa onde você precisa repetir toda a informação a cada nova fala.
  - Stateful é como uma conversa onde as informações anteriores são lembradas e você pode continuar de onde parou.

**Exemplo Prático:**
  - Stateless: Cada requisição ao servidor de uma aplicação web traz consigo todas as informações necessárias para processamento.
  - Stateful: Uma aplicação que mantém um login contínuo, lembrando quem está autenticado entre diferentes requisições.

Em resumo, a diferença essencial está na presença ou ausência de armazenamento de estado entre requisições. Sistemas stateless são mais simples e escaláveis, enquanto sistemas stateful podem oferecer maior personalização, lembrando o contexto das interações anteriores.