<h2> Construindo um projeto com arquitetura baseada em microsserviços usando Spring Cloud</h2>

Para clonar o projeto(com GitHub Cli)
```
gh repo clone claudioneves1981/dio-experts-session
```
para criar o conteiner com Elasticsearch e Redis 
Rode na pasta dio-experts-session (de preferencia use uma distribuição linux para rodar o projeto, eu usei Ubuntu 20.04)

sudo docker-compose up -d

Para executar os serviços vc pode abrir via ide, ou subir individualmente em cada pasta
utilizando gradle como no comando abaixo. (Suba primeito os serviços config-server , service-discovery e gateway e depois product-catalog e shopping-cart)

```shell script
./gradlew bootRun 
```

Após executar o comando acima em cada pasta, vc pode verificar se os serviços estão ativos acessando o localhost na porta 9000(Eureka)

```
http://localhost:9000/
```

São necessários os seguintes pré-requisitos para a execução do projeto:

* Java 8 ou versões superiores.
* Gradle
* Intellj IDEA Community Edition ou sua IDE favorita.
* Controle de versão GIT instalado na sua máquina.
* GitHub Cli instalado na sua maquina.
* Conta no GitHub para o armazenamento do seu projeto na nuvem.
* Conhecimento basico de Elasticsearch e Redis.
* Docker instalado em sua maquina.

Abaixo, seguem links dos principais recursos usados no projeto.

* [Referência do Intellij IDEA Community, para download](https://www.jetbrains.com/idea/download)
* [Palheta de atalhos de comandos do Intellij](https://resources.jetbrains.com/storage/products/intellij-idea/docs/IntelliJIDEA_ReferenceCard.pdf)
* [Site oficial do Spring](https://spring.io/)
* [Site oficial do Spring Initialzr, para setup do projeto](https://start.spring.io/)
* [Site oficial do GIT](https://git-scm.com/)
* [Site oficial do GitHub](http://github.com/)
* [Github Cli](https://cli.github.com/)
* [Referência para o padrão arquitetural REST](https://restfulapi.net/)
* [Site oficial do Docker](https://www.docker.com/)
* [Site Oficial do Elasticsearch](https://www.elastic.co/pt/elasticsearch/)
* [Site Oficial do Redis](https://redis.io/)
* [Eureka Netflix Spring Cloud](https://spring.io/projects/spring-cloud-netflix)
* [Dio Experts Config / Oswaldo Neto](https://github.com/oswaldoneto/dio-experts-config)
