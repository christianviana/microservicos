## Repositório com microservicos para testes e aprendizado Completo com balanceador de carga, eureka gateway, microservicos e filas rabbitmq ##

- Para que os microserviços e filas funcionem, é necessário levantar os contêineres de banco de dados e do rabbitmq executando ```docker compose up``` na pasta do arquivo docker-compose.yml.
- Também será necessário inicializar os projetos Eureka de api-gateway (```gateway```) e service registry (```server```), seja via IDE ou via linha de comando, usando ```mvn spring-boot:run```
  
