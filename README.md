# Api REST e RESTFul
   Uma API é um conjunto de definições e protocolos usado no desenvolvimento e na integração de aplicações. Às vezes, APIs são descritas como um contrato entre um provedor e um usuário de informações, estabelecendo o conteúdo exigido pelo consumidor (a chamada) e o conteúdo exigido pelo produtor (a resposta).
   Você pode pensar em uma API da Web como um gateway entre clientes e recursos na Web, onde os clientes são usuários que desejam acessar informações da Web podendo ser uma pessoa ou um sistema de software que usa a API e os recursos são as informações que diferentes aplicações fornecem aos seus clientes. Os recursos podem ser imagens, vídeos, textos, números ou qualquer tipo de dado. A máquina que fornece o recurso ao cliente também é chamada de servidor. As organizações usam APIs para compartilhar recursos e fornecer serviços da Web, mantendo a segurança, o controle e a autenticação.
- A arquitetura REST (Representational State Transfer - Transferência de Estado Representacional): é um paradigma de software que estabelece diretrizes específicas sobre como uma API deve operar. Inicialmente concebida como uma abordagem para gerenciar a comunicação em redes complexas, como a internet, a REST se tornou uma estrutura essencial para possibilitar a comunicação eficiente, confiável e de alto desempenho em larga escala, os desenvolvedores podem criar APIs que facilitam a interação entre sistemas distribuídos. Esses princípios incluem a representação de recursos como entidades distintas identificadas por URIs (Uniform Resource Identifiers), a utilização dos métodos HTTP padrão para operações específicas, e a transferência de representações de estado dos recursos entre cliente e servidor.
- A API RESTful é uma interface que possibilita a troca segura de informações entre dois sistemas de computador pela internet. Em muitas aplicações de negócios, a necessidade de comunicação entre sistemas internos e de terceiros é fundamental para realizar diversas tarefas operacionais. 
Essas APIs suportam eficientemente a troca de informações ao aderir a padrões de comunicação de software que são seguros, confiáveis e eficientes. Ao seguir os princípios da arquitetura REST, como a utilização dos métodos HTTP padrão e a representação de recursos identificados por URIs, as APIs RESTful garantem uma integração consistente e flexível entre sistemas. Essa abordagem facilita a interoperabilidade, permitindo que diferentes sistemas se comuniquem de maneira padronizada, promovendo assim a automação eficiente de processos e a colaboração entre sistemas heterogêneos.

## Diferenças entre REST e RESTFul   
   API REST é uma abordagem arquitetural, enquanto uma API RESTful é uma implementação específica dessa arquitetura, seguindo boas práticas e padrões definidos pela abordagem REST. Ambas visam promover uma comunicação eficiente e escalável entre sistemas distribuídos.
   **REST** (Representational State Transfer) é um estilo arquitetural proposto por Roy Fielding em sua tese de doutorado em 2000. Ele define princípios para o desenvolvimento de serviços web, promovendo simplicidade, escalabilidade e interoperabilidade. Os fundamentos do REST incluem o uso dos métodos HTTP (GET, POST, PUT, DELETE) para operações CRUD, a identificação de recursos por URIs (Uniform Resource Identifiers), representação de recursos em formatos como XML ou JSON, e uma comunicação sem estado.
   
Por outro lado, **RESTful** é um termo utilizado para descrever sistemas, serviços ou APIs que seguem os princípios estabelecidos pelo REST. Assim, quando um serviço é considerado RESTful, significa que ele adere às práticas e diretrizes do REST. Isso envolve o uso apropriado dos métodos HTTP, URIs significativas, representação adequada de recursos e a manutenção da ausência de estado compartilhado entre o cliente e o servidor.
    
## HTTP verbs

Métodos de Requisição (HTTP Verbs):
- [x] GET

Utilizado para requisitar dados de um recurso específico no servidor.
- [x] POST:

Envia dados para o servidor para criar um novo recurso.
- [x] PUT:

Atualiza ou cria um recurso no servidor com base nos dados fornecidos.
- [x] DELETE:

Remove um recurso específico no servidor.
- [x] PATCH:

Aplica modificações parciais a um recurso.
- [x] HEAD:

Similar ao GET, mas solicita apenas os cabeçalhos, sem o corpo da resposta.
- [x] OPTIONS:

Fornece informações sobre as opções de comunicação disponíveis para o recurso alvo.
- [x] TRACE:

Utilizado para testar a conectividade, exibindo o que foi recebido no servidor de volta ao cliente.


 ## HTTP Status Code
1 - Informativo:
Esta classe sinaliza respostas provisórias e indica que o servidor recebeu a solicitação e está continuando a processá-la. Esses códigos são mais informativos do que executáveis e incluem respostas como 100 (Continuar), indicando que a parte inicial da solicitação foi recebida e o cliente deve prosseguir com o restante.

2 - Sucesso:
Códigos de sucesso confirmam que a solicitação do cliente foi recebida, compreendida e aceita com sucesso. O famoso código 200 (OK) indica que a solicitação foi bem-sucedida, e o servidor está entregando o recurso solicitado. Outro código comum é 204 (Sem Conteúdo), sugerindo que o servidor processou com sucesso a solicitação, mas não está retornando nenhum conteúdo.

3 - Redirecionamento:
Esses códigos indicam que é necessário tomar medidas adicionais para completar a solicitação. Por exemplo, 301 (Movido Permanentemente) informa ao cliente que o recurso solicitado foi movido permanentemente para uma nova localização. Da mesma forma, 302 (Encontrado) indica um redirecionamento temporário.

4 - Erro do Cliente:
Códigos de erro do cliente apontam para problemas no lado do cliente da conexão. O infame código 404 (Não Encontrado) sinaliza que o recurso solicitado não pôde ser encontrado no servidor. Outro código comum, 403 (Proibido), sugere que o cliente não possui permissão para acessar o recurso solicitado.

5 - Erro do Servidor:
Códigos de erro do servidor indicam que o servidor falhou em atender a uma solicitação válida. O código frequentemente encontrado 500 (Erro Interno do Servidor) é uma mensagem genérica indicando que uma condição inesperada impediu o servidor de atender à solicitação. Esta classe também inclui códigos como 503 (Serviço Indisponível), indicando que o servidor está temporariamente incapaz de lidar com a solicitação.

--- Autor do resumo: Ellen Virginia - 01570521

