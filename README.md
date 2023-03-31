# springboot_security_Jwt

#### set up your application.yml with these 
`
spring:

  datasource:

    url: jdbc:postgresql://localhost:5432/database-name

    username:your username

    password: your password

    driver-class-name: org.postgresql.Driver

  jpa:

    hibernate:
      ddl-auto: create-drop

    show-sql: true
    properties:
      hibernate:
        format_sql: true
      database: postgresql
      database-platform: org.hibernate.dialect.PostgreSQLDialect
`
### running on localhost:8080
### swagger 
[http://localhost:8080/swagger-ui/index.html]