# GraphQL

## Diferença entre REST e GraphQl

REST (Representational State Transfer):

É uma abordagem comum para criar APIs (Interfaces de Programação de Aplicações) em sistemas web.
Utiliza endpoints específicos para diferentes recursos, e os clientes solicitam esses recursos através de requisições HTTP (como GET, POST, etc.).
A resposta geralmente inclui todos os dados disponíveis para o recurso, e o cliente precisa analisar e extrair as informações desejadas.
GraphQL:

É uma linguagem de consulta para APIs, introduzindo uma abordagem mais flexível.
Permite que os clientes solicitem apenas os dados necessários, evitando excesso ou falta de dados na resposta.
O cliente especifica a estrutura exata dos dados que deseja, e a API responde com um payload contendo apenas esses dados, facilitando a eficiência na transferência de informações.
Comparação Simples:

REST é como ir a um buffet onde os pratos estão pré-determinados, e você escolhe os que deseja.
GraphQL é como um menu personalizado, onde você especifica exatamente os pratos e ingredientes desejados.
Exemplo Prático:

REST: Para obter informações sobre um usuário, você pode ter um endpoint específico /users/123.
GraphQL: Você faz uma consulta, como query { user(id: 123) { name, email } }, recebendo apenas os dados desejados.
Em resumo, enquanto o REST oferece um conjunto fixo de endpoints para diferentes recursos, o GraphQL permite que os clientes solicitem dados de forma mais flexível, especificando exatamente o que precisam, resultando em respostas mais eficientes e personalizadas.