# FaturaCartaoCreditoJob
Geração de fatura do cartão de crédito

# Configuração

Acesse o arquivo "application.properties" adicione a configuração da sua base de dados, caso esteja utililzando o sistema operacional Windows adicione após o seu banco de dados o "?useUnicode=true&characterEnconding=UTF-8?useTimezone=true&serverTimezone=UTC".
```
spring.datasource.jdbcUrl=jdbc:mysql://localhost:3306/spring_batch
spring.datasource.username=user
spring.datasource.password=passwrod
app.datasource.jdbcUrl=jdbc:mysql://localhost:3306/fatura_cartao_credito
app.datasource.username=user
app.datasource.password=password
spring.batch.initialize-schema=always

```

