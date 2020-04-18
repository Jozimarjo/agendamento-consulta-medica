# agendamento-consulta-medica

## Descrição do Projeto
* Para acessar o Sistemas o usuario devera criar um cadastro inserindo nome,email e senha. Senha devera conter no minimo 6 digitos
* Usuario podera agendar uma consulta com um medico cadastrado atraves do sistema.
* Podera visualizar suas consultas marcadas
### Google Cloud
Obs: não esta comunicando com o back
front-end: http://agendamento-medico-274205.appspot.com/login


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
$ docker-compose up -d
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
