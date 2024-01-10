#GRPC

## gRPC (gRPC Remote Procedure Call):

É um framework de código aberto desenvolvido pelo Google.
Facilita a comunicação eficiente entre sistemas distribuídos, permitindo que serviços em diferentes locais troquem informações de maneira eficaz.
Usa o protocolo HTTP/2 para transporte e o Protocol Buffers (protobuf) como formato de serialização, o que o torna eficiente e compacto.
É baseado no conceito de chamadas de procedimento remoto (RPC), onde um serviço pode chamar métodos em um servidor remoto como se fossem métodos locais.
Comparação Simples:

Se REST é como enviar cartas (requisições HTTP) para obter informações, gRPC é como fazer uma chamada telefônica direta (chamada de procedimento remoto) para interagir com um serviço.
Exemplo Prático:

Se você tem um serviço que fornece informações sobre livros e outro que fornece informações sobre autores, usando gRPC, você pode chamar métodos diretamente em cada serviço para obter as informações necessárias, em vez de fazer várias requisições HTTP separadas.
Em resumo, gRPC é uma tecnologia que simplifica e melhora a comunicação entre diferentes partes de um sistema distribuído, usando chamadas de procedimento remoto eficientes e um formato compacto para troca de dados.