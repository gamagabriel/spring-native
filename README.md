## Como Compilar spring-native

Para gerar build -> ./mvnw spring-boot:build-image

Checar nome do build gerado -> docker images

Executar image -> docker run — name <image-name> -p 8080:8080 <image-name>:1.0.0
