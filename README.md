# gerenciador-salas-reunioes

This project was developed to training about creating an API REST using Java with Spring Boot, an Angular application and integrate frontend with backend on Everis bootcamp course "Crie seu gerenciador de salas de reuniões com Java e Angular" from "Digital Innovation One" plataform.

To see this project working access the URLs below
 - Backend (API REST): "https://gerenciador-salas-de-reuniao.herokuapp.com/api/v1/rooms"
 - Frontend: "https://front-gerenciador-salas.herokuapp.com"

## Gerenciador de salas de reunioes

### Stack utilizada:


 * Spring Web
 * Spring Data JPA
 * H2 Database
 * Java 8
 * Maven
 * Angular 
 * RxJS
 
### Endpoints criados na API

* Criar sala de reuniao
POST - /api/v1/rooms

* Listar todas as salas
GET - /api/v1/rooms

* Buscar uma sala pelo Id
GET - /api/v1/rooms/{id}

* Atualizar uma sala pelo Id
PUT - /api/v1/rooms/{id}

* Excluir uma sala pelo id
DELETE - /api/v1/rooms/{Id}
