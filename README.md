## API
_Application Programming Interface_  
Conjunto de rotinas e padrões estabelecidos por uma aplicação para que outras aplicações possam usar as funcionalidades desta aplicação

- Responsável por estabelecer conexão entre serviços
- Intermediador para trocar informações

## REST
_Representational State Transfer_  
Será feita uma transferencia de dados de uma maneira, simbólica, figurativa, representativa, de maneira didática   
A transferencia de dados geralmente é feita usando o protocolo HTTP   
O Rest delimita obrigações nessas transferencias de dados

## RESTful
### Seis necessidades para ser RESTful
- _Client-Server_: Separação do cliente e do armazenamento de dados (servidor)
- _Stateless_: Cada requisição que o cliente faz para o servidor deverá ter as informações necessárias para o servidor entender enviar uma _RESPONSE_ (resposta) para a _REQUEST_ (requisição)

# Roteiro
[Apostila Java](https://www.alura.com.br/apostila-java-orientacao-objetos)

[ ] RESTful APIs  
[ ] Beans no Spring  
[ ] Spring Boot Peripherals  
[ ] Spring Data  
[ ] Como Dockerizar Aplicações Spring  
[ ] Test Containers  
[ ] REST e Service  
[ ] Components e Service no Spring  
[ ] Debugging e Leitura de Código  

### RESTful APIs
- Conceitos de arquitetura REST
- Implementação de endpoints RESTful no Spring Boot
- Boas práticas para criar APIs REST status codes, métodos HTTP

### Beans no Spring
- O que são Beans e como são gerenciados pelo Spring.
- Ciclo de vida dos Beans.
- Escopos de Beans (Singleton, Prototype, etc.)

### Spring Boot Peripherals
- Introdução ao Spring Boot e como ele facilita a configuração.
- Utilização de Starters no Spring Boot.
- Profiles e propriedades no Spring Boot (application.properties, YAML).

### Spring Data
- Integração com bancos de dados usando Spring Data JPA.
- Criação de repositórios (Repositories) e consultas personalizadas.
- Uso de Query Methods e @Query.

### Como Dockerizar Aplicações Spring
- Criando um Dockerfile para um projeto Spring Boot.
- Configuração de volumes, networks e environment variables no Docker.
- Execução de contêineres e orquestração com Docker Compose.

### Test Containers
- O que são Test Containers.
- Como usar Test Containers para testes de integração em Spring.
- Exemplos práticos com banco de dados e outros serviços.

### REST e Service
- Diferenças entre camadas REST (Controller) e Service no Spring.
- Boas práticas na separação de responsabilidades.

### Components e Service no Spring
- Diferença entre @Component, @Service e @Repository.
- Como e quando usar cada anotação.
- Injeção de dependências e autowiring.

### Debugging e Leitura de Código
- Como usar o depurador (debugger) em IDEs como IntelliJ ou Eclipse.
- Ferramentas de logging e tracing.
- Leitura de logs e erros comuns.