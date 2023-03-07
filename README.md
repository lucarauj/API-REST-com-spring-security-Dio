# API-REST-com-spring-security-Dio

Dependências:

- Web
- Spring Security
- Spring Data JPA
- H2 Database

Autenticação Simples ```application.properties```:

```
spring.security.user.name=user
spring.security.user.password=user123
spring.security.user.roles=USERS
```

Autenticação de usuário e perfis de acesso:


Anotações:

@Configuration
@EnableWebSecurity
@EnableGlobalMethodSecurity
@RestController
@GetMapping
@PreAuthorize
@Entity
@Table
@Id
@GeneratedValue(strategy = GenerationType.IDENTITY)
@Column
@ElementCollection(fetch = FetchType.EAGER)
@CollectionTable
@JoinColumn
@Query
@Param
@Autowired
@Service
@Component
@Transactional
