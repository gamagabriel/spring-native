## Como Compilar spring-native

Para buildar o projeto precisaremos executar o comando abaixo:
./mvnw spring-boot:build-image

Após buildarmos, precisaremos checar o nome da imagem criada, usando o comando abaixo:
docker images

Após verificarmos a imagem criada, precisaremos executar este comando para rodar o contexto:
docker run — name spring-kotlin-microservice -p 8080:8080 spring-kotlin-microservice:1.0.0
