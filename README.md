## Como Compilar spring-native

Para gerar build -> mvn -Pnative spring-boot:build-image

Executar image -> $ docker run --rm -p 8080:8080 docker.io/library/myproject:0.0.1-SNAPSHOT
