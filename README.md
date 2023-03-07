[![NPM](https://img.shields.io/npm/l/react)](https://github.com/lucarauj/API-REST-com-spring-security-Dio/blob/main/LICENSE)

<h1 align="center"> API REST</h1>
<h2 align="center"> Com Spring Security </h2>

<p align="center"><img width="450px" src="https://github.com/lucarauj/assets/blob/main/SpringSecurity.png" /></p>

### ⛏ Criação do projeto base com as seguintes dependências:

- Web
- Spring Security
- Spring Data JPA
- H2 Database

## Adicionando Dependência do Spring Security a um projeto ```pom.xml``` [Clique na Pasta 🖱](https://github.com/lucarauj/API-REST-com-spring-security-Dio/tree/main/spring-security-1-habilitando-seguranca-com-spring)

```
<dependency>
  <groupId>org.springframework.security</groupId>
  <artifactId>spring-security-test</artifactId>
  <scope>test</scope>
</dependency>
<dependency>
  <groupId>org.springframework.boot</groupId>
  <artifactId>spring-boot-starter-security</artifactId>
</dependency>
```

## Autenticação Simples [Clique na Pasta 🖱](https://github.com/lucarauj/API-REST-com-spring-security-Dio/tree/main/spring-security-2-autenticacao-simples)

### ⚙ Configurando o arquivo ```application.properties``` :

```
spring.security.user.name=user
spring.security.user.password=user123
spring.security.user.roles=USERS
```

## Utilizando WebSecurityConfigurerAdapter para Permissão de acesso [Clique na Pasta 🖱](https://github.com/lucarauj/API-REST-com-spring-security-Dio/tree/main/spring-security-3-configure-adapter)

## Autenticação com Banco de dados [Clique na Pasta 🖱](https://github.com/lucarauj/API-REST-com-spring-security-Dio/tree/main/spring-security-4-autenticacao-com-banco-de-dados)

### 📝 Anotações:

- @Autowired
- @Configuration
- @Component
- @CollectionTable
- @Column
- @EnableWebSecurity
- @EnableGlobalMethodSecurity
- @Entity
- @ElementCollection(fetch = FetchType.EAGER)
- @GetMapping
- @GeneratedValue(strategy = GenerationType.IDENTITY)
- @Id
- @JoinColumn
- @Param
- @PreAuthorize
- @Query
- @RestController
- @Service
- @Table
- @Transactional



### 🚀 Principais tecnologias utilizadas no projeto:

<div style="display: inline_block"><br>
<img align="center" alt="Lucarauj-Java" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg">
<img align="center" alt="Lucarauj-Postman" height="50" width="90" src="https://github.com/lucarauj/assets/blob/main/postman.png">
<img align="center" alt="Lucarauj-Spring" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg">
<img align="center" alt="Lucarauj-SpringBoot" height="40" width="110" src="https://github.com/lucarauj/assets/blob/main/SpringBoot.jpeg">
<img align="center" alt="Lucarauj-Maven" height="50" width="60" src="https://github.com/lucarauj/assets/blob/main/Maven-Apache.svg">
<img align="center" alt="Lucarauj-H2" height="30" width="30" src="https://github.com/lucarauj/assets/blob/main/H2.png">
</div>


## Autor

#### Lucas Araujo

<a href="https://www.linkedin.com/in/lucarauj"><img alt="lucarauj | LinkdeIN" width="40px" src="https://user-images.githubusercontent.com/43545812/144035037-0f415fc7-9f96-4517-a370-ccc6e78a714b.png" /></a>
