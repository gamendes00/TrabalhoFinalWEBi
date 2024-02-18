<div align="center">
  <h2>EagleFlicks</h2>
  <p>Plataforma de streaming de filmes online.</p>
</div>

## Requisitos previos
- Java 17
- [Spring Tool Suite 4](https://spring.io/tools) ou qualquer IDE compatível com Spring.
- [Visual Studio Code](https://code.visualstudio.com/) ou outro editor de texto.
- [Node.js](https://nodejs.org/) e [Angular CLI](https://angular.io/cli) para o frontend.
- [MySQL](https://www.mysql.com/) ou qualquer banco de dados compatível com MySQL.

## Instalação e Execução
1. Clone ou baixe o repositório `https://github.com/NeiDenn/spring-angular-eagleflicks.git`
2. Importe o projeto “project-backend” no IDE Spring Tool Suite 4 e “project-frontend” no Visual Studio Code.
3. Ajustar no arquivo `application.properties` a cadeia de conexão `BD_EAGLEFLICKS`
```
server.port=8091
spring.jpa.database=MYSQL
spring.jpa.show-sql=true
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url=jdbc:mysql://localhost:3306/BD_EAGLEFLICKS?serverTimezone=UTC
spring.datasource.username=root
spring.datasource.password=mysql
```

4. Eexecute o banco de dados mysql `BD_EAGLEFLICKS`
5. Inicie o servidor back-end Spring.
6. Inicie o servidor front-end Angular para iniciar a IU. `ng serve -o`
7. Depois de iniciar o backend Spring e o frontend Angular, você poderá acessar o aplicativo em seu navegador:

- Backend: http://localhost:8091
- Frontend: http://localhost:4200
