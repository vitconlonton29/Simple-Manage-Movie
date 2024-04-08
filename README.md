# REST API of Movie Information System
> Simple Movie Information System using Java Spring Boot


## Documentation 

| Method | Url | Role Privilege | Action |
| --- | --- | --- | --- |
| `POST` | http://localhost:8080/api/v1/auth/register | ALL | Register admin / user |
| `POST` | http://localhost:8080/api/v1/auth/login | ALL | Login admin / user |
| `GET` | http://localhost:8080/api/v1/genre | ALL | Get all genre |
| `GET` | http://localhost:8080/api/v1/genre/{id} | ALL | Get genre by id |
| `POST` | http://localhost:8080/api/v1/genre | ADMIN | Create genre |
| `POST` | http://localhost:8080/api/v1/genre/{id} | ADMIN | Update genre by id |
| `DELETE` | http://localhost:8080/api/v1/genre/{id} | ADMIN | Delete genre by id |
| `GET` | http://localhost:8080/api/v1/movie | ALL | Get all movie |
| `GET` | http://localhost:8080/api/v1/movie/{id} | ALL | Get movie by id |
| `POST` | http://localhost:8080/api/v1/movie | ADMIN | Create movie |
| `POST` | http://localhost:8080/api/v1/movie/{id} | ADMIN | Update movie by id |
| `DELETE` | http://localhost:8080/api/v1/movie/{id} | ADMIN | Delete movie by id |
| `GET` | http://localhost:8080/api/v1/review | ALL | Get all review |
| `GET` | http://localhost:8080/api/v1/review/{id} | ALL | Get review by id |
| `POST` | http://localhost:8080/api/v1/review | USER | Create review |
| `POST` | http://localhost:8080/api/v1/review/{id} | USER | Update review by id |
| `DELETE` | http://localhost:8080/api/v1/review/{id} | USER | Delete review by id |



