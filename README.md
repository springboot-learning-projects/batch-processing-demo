# batch-processing-demo
## application.properties

```
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.url = jdbc:mysql://localhost:3306/javatechie
spring.datasource.username = root
spring.datasource.password = YOUR_PASSWORD
spring.jpa.show-sql = true
spring.jpa.hibernate.ddl-auto = update
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5Dialect
server.port=9191
spring.batch.initialize-schema=ALWAYS

#disabled job run at startup
spring.batch.job.enabled=false
```
![one](demo/1.png)