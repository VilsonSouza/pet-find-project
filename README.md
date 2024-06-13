# petFind

Bem-vindo ao projeto **petFind**, uma aplicação para facilitar a localização de animais de estimação perdidos e encontrados.

## Tecnologias Utilizadas

- **Java**
- **Spring Boot**
- **H2 Database**
- **Swagger UI**

## URLs Importantes

- **Swagger UI**: [http://localhost:8080/swagger-ui/index.html](http://localhost:8080/swagger-ui/index.html)
- **H2 Console**: [http://localhost:8080/h2/](http://localhost:8080/h2/)

## Como Executar o Projeto

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/petFind.git
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd petFind
    ```
3. Execute a aplicação com o Maven:
    ```bash
    ./mvnw spring-boot:run
    ```

## Configurações do Banco de Dados

A aplicação está configurada para usar o banco de dados H2 em memória. Você pode acessar o console do H2 Database para visualizar e gerenciar o banco de dados usando a URL fornecida acima.

As configurações do banco de dados podem ser encontradas no arquivo `application.properties`:
```properties
spring.datasource.url=jdbc:h2:mem:{database-name}
spring.datasource.driverClassName=org.h2.Driver
spring.datasource.username={username}
spring.datasource.password={password}
spring.h2.console.enabled=true
spring.h2.console.path=/{path}
