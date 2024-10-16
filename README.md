## :computer: API
_Application Programming Interface_  
Conjunto de rotinas e padrões estabelecidos por uma aplicação para que outras aplicações possam usar as funcionalidades da mesma.
- Responsável por estabelecer conexão entre serviços.
- Intermediador para trocar informações.

## :calling: REST
_Representational State Transfer_  
Será feita uma transferencia de dados de uma maneira representativa ou didática.   
- A transferencia de dados geralmente é feita usando o protocolo HTTP.   
- O Rest delimita obrigações nessas transferencias de dados.

## :bulb: RESTful
### Necessidades para ser RESTful
- _Client-Server_: Separação do cliente e do armazenamento de dados (servidor).

- _Stateless_: Cada requisição que o cliente faz para o servidor deverá conter todas as informações necessárias para o servidor entender e enviar uma _RESPONSE_ (resposta) para a _REQUEST_ (requisição).

- _Cacheable_: As respostas de uma requisição deverão ser explícitas ao dizer se aquela requisição pode ou não ser cacheada pelo cliente.

- _Layered System_: O cliente acessa um endpoint sem precisar saber da complexidade, quais passos estão sendo percorridos para o servidor responder a requisição, ou quais outras camadas o servidor estará lidando para que que a requisição seja respondida.

#### Opcional
- _Code on Demand_: Dá a possibilidade da aplicação pegar códigos, como o JavaScript por exemplo, e executar no cliente. 

# Roteiro
[Apostila Java](https://www.alura.com.br/apostila-java-orientacao-objetos)

<!-- Alterar os links após atualizar a checkbox -->
- [ ] [RESTful APIs](#white_check_mark--restful-apis)  
- [ ] [Beans no Spring](#grey_exclamation--beans-no-spring)
- [ ] [Spring Boot Peripherals](#grey_exclamation--spring-boot-peripherals)
- [ ] [Spring Data](#grey_exclamation--spring-data)
- [ ] [Como Dockerizar Aplicações Spring](#grey_exclamation--como-dockerizar-aplicações-spring)
- [ ] [Test Containers](#grey_exclamation--test-containers)
- [ ] [REST e Service](#grey_exclamation--rest-e-service)
- [ ] [Components e Service no Spring](#grey_exclamation--components-e-service-no-spring)
- [ ] [Debugging e Leitura de Código](#grey_exclamation--debugging-e-leitura-de-código)

### :white_check_mark: <!-- :grey_exclamation: --> RESTful APIs
- Conceitos de arquitetura REST
- Implementação de endpoints RESTful no Spring Boot
- Boas práticas para criar APIs REST status codes, métodos HTTP

### :grey_exclamation: <!-- :white_check_mark: --> Beans no Spring
- O que são Beans e como são gerenciados pelo Spring.
- Ciclo de vida dos Beans.
- Escopos de Beans (Singleton, Prototype, etc.)

### :grey_exclamation: <!-- :white_check_mark: --> Spring Boot Peripherals
- Introdução ao Spring Boot e como ele facilita a configuração.
- Utilização de Starters no Spring Boot.
- Profiles e propriedades no Spring Boot (application.properties, YAML).

### :grey_exclamation: <!-- :white_check_mark: --> Spring Data
- Integração com bancos de dados usando Spring Data JPA.
- Criação de repositórios (Repositories) e consultas personalizadas.
- Uso de Query Methods e @Query.

### :grey_exclamation: <!-- :white_check_mark: --> Como Dockerizar Aplicações Spring
- Criando um Dockerfile para um projeto Spring Boot.
- Configuração de volumes, networks e environment variables no Docker.
- Execução de contêineres e orquestração com Docker Compose.

### :grey_exclamation: <!-- :white_check_mark: --> Test Containers
- O que são Test Containers.
- Como usar Test Containers para testes de integração em Spring.
- Exemplos práticos com banco de dados e outros serviços.

### :grey_exclamation: <!-- :white_check_mark: --> REST e Service
- Diferenças entre camadas REST (Controller) e Service no Spring.
- Boas práticas na separação de responsabilidades.

### :grey_exclamation: <!-- :white_check_mark: --> Components e Service no Spring
- Diferença entre @Component, @Service e @Repository.
- Como e quando usar cada anotação.
- Injeção de dependências e autowiring.

### :grey_exclamation: <!-- :white_check_mark: --> Debugging e Leitura de Código
- Como usar o depurador (debugger) em IDEs como IntelliJ ou Eclipse.
- Ferramentas de logging e tracing.
- Leitura de logs e erros comuns.