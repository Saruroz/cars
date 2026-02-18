# 🚗 Cars API — Spring Boot REST

API REST para gestión de vehículos construida con Java y Spring Boot. Permite realizar operaciones CRUD completas sobre un catálogo de coches.

---

## 🛠️ Tecnologías utilizadas

- **Java 17+**
- **Spring Boot**
- **Spring Data JPA**
- **Maven**
- **REST API**



---

## 📋 Endpoints disponibles

| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `GET` | `/cars` | Obtener todos los coches |
| `GET` | `/cars/{id}` | Obtener un coche por ID |
| `POST` | `/cars` | Crear un nuevo coche |
| `PUT` | `/cars/{id}` | Actualizar un coche |
| `DELETE` | `/cars/{id}` | Eliminar un coche |

*(Personaliza estos endpoints con los que tengas realmente en el proyecto)*

---

## ▶️ Cómo ejecutar el proyecto localmente

### Requisitos previos
- Java 17 o superior
- Maven 3.x

### Pasos

```bash
# 1. Clonar el repositorio
git clone https://github.com/Saruroz/cars.git
cd cars

# 2. Compilar el proyecto
mvn clean install

# 3. Ejecutar la aplicación
mvn spring-boot:run
```

La API estará disponible en: `http://localhost:8080`

---

## 📦 Ejemplo de request

```json
POST /cars
Content-Type: application/json

{
  "brand": "Toyota",
  "model": "Corolla",
  "year": 2022,
  "color": "Blanco"
}
```

---

## 🗂️ Estructura del proyecto

```
src/
├── main/
│   ├── java/
│   │   └── com/example/cars/
│   │       ├── controller/    # Controladores REST
│   │       ├── model/         # Entidades
│   │       ├── repository/    # Acceso a datos (JPA)
│   │       └── service/       # Lógica de negocio
│   └── resources/
│       └── application.properties
```

---

## 👤 Autor

**Santiago Ruiz** · [GitHub](https://github.com/Saruroz) · [LinkedIn](https://www.linkedin.com/in/santiago-arr/)
