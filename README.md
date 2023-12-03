# Api REST e RESTFUl

Uma API REST, que significa Interface de Programação de Aplicações baseada na Transferência de Estado Representacional, compreende um conjunto de princípios arquitetônicos orientados ao desenvolvimento de serviços online. Essa abordagem faz uso do protocolo HTTP
para facilitar a comunicação e se fundamenta em conceitos como recursos, Identificadores Uniformes de Recursos (URI) e a representação e manipulação de estados.

## Diferenças entre REST e RESTFUl

- REST (Representational State Transfer): É um estilo arquitetural usado para criar serviços web. Ele sugere usar métodos HTTP (como GET, POST) e destaca à importância de representar recursos com URIs (Uniform Resource Identifiers).

- RESTful: Isso é basicamente seguir as ideias do REST na prática. Um serviço é chamado de "RESTful" quando põe em prática as sugestões do REST. Isso incluí usar direito os métodos HTTP, lidar com recursos usando URIs, e trabalhar sem guardar informações sobre o
estado da sessão no servidor. Em resumo, é como botar em prática os conceitos do REST num serviço web.

Resumindo, REST é a ideia e RESTful é colocar essa ideia em ação.

## HTTP verbs

Cada verbo tem uma função específica na interação entre clientes e servidores web, proporcionando operações distintas para manipular recursos na internet.

- GET: Obtém dados de um recurso.
- POST: Envia dados para criar um novo recurso.
- PUT: Atualiza ou cria um recurso.
- DELETE: Remove um recurso.
- PATCH: Aplica modificações parciais a um recurso.
- HEAD: Obtém apenas os cabeçalhos de um recurso.
- OPTIONS: Obtém os métodos HTTP suportados para um recurso.
- TRACE: Realiza um teste de loop-back para o recurso de destino.
- CONNECT: Estabelece um túnel para o servidor identificado por um recurso alvo.

## HTTP Status Code

Os códigos de status HTTP são números de três dígitos que indicam o resultado de uma solicitação HTTP. Eles informam sobre o sucesso, redirecionamento, erros do cliente ou erros do servidor. Por exemplo:

- 1xx (Informational): A solicitação foi recebida, continua o processo e que o cliente deve aguardar.
    - 

- 2xx (Successful): A solicitação foi recebida, entendida e aceita com sucesso.
    - 200 OK: A solicitação foi bem-sucedida.

- 3xx (Redirection): A solicitação precisa de ações adicionais para ser completada.
    - 302 Found: Recurso encontrado temporariamente em uma nova localização.

- 4xx (Client Error): Indica que ocorreu um erro por parte do cliente.
    - 404 Not Found: O recurso solicitado não foi encontrado no servidor.

---

Autor do resumo: Luiz Felipe de Sousa Sá - 01532557
