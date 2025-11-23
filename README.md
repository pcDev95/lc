# Live Counter (LC)

## Technology Stack

| Technology | Version |
|------------|---------| 
| **Java** | 21 |
| **Spring Boot** | 3.3.5 |
| **Spring Data JPA** | 3.3.5 (via Spring Boot) |
| **Spring Web** | 3.3.5 (via Spring Boot) |
| **H2 Database** | Runtime (managed by Spring Boot) |
| **Lombok** | Managed by Spring Boot |
| **SpringDoc OpenAPI** | 2.6.0 |
| **Maven** | 3.6+ |

## Build & Run

```bash
# Build
./mvnw clean install

# Run
./mvnw spring-boot:run
```

## Endpoints

- **SSE Counter**: `http://localhost:8080/counter`
- **H2 Console**: `http://localhost:8080/h2-console`
- **Swagger UI**: `http://localhost:8080/swagger-ui.html`
