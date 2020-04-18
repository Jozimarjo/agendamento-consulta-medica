# agendamento-consulta-medica
## Descrição do Projeto
* Para acessar o Sistemas o usuario devera criar um cadastro inserindo nome,email e senha. Senha devera conter no minimo 6 digitos
* Usuario podera agendar uma consulta com um medico cadastrado atraves do sistema.
* Podera visualizar suas consultas marcadas
### Back-end
* Maven
* Spring Boot
* Cloud sql postgres
* Hibernate
* Jpa

### Front-end
* Angular 8
* Angular-Material

## Configuração e Execução

### Docker
Foi disponibilizado um arquivo docker-compose.yml contendo os conteiners necessários à execução, já configurados. Para executar a aplicação usando docker, basta executar o compose.

docker-compose up
```bash
$ docker-compose up
```

O front-end será executado na porta 4200 (http://localhost:4200) e o back-end será executado na porta 8080 (http://localhost:8080).

### Execução Local
Front-end
Na pasta front-end, digite:

npm install

npm start

O front-end será executado em http://localhost:3000.

#### Back-end
Na pasta back-end, digite:

mvn spring-boot:run

O back-end será executado em http://localhost:8080.
