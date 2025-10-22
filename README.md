# RestInn API 🛎️

API **RESTful** para la **gestión integral de un sistema hotelero**, que incluye la administración de **clientes**, **reservas**, **habitaciones**, **facturación** y **empleados**.

Permite realizar operaciones **CRUD** sobre los distintos recursos, con **acceso remoto a base de datos MySQL** y **protección mediante Spring Security**.  
Diseñada para integrarse fácilmente con sistemas de gestión hotelera front-end o aplicaciones externas.

## 🧩 Funcionalidades principales
- Gestión de clientes, empleados y habitaciones.
- Administración de reservas y facturación.
- API RESTful con endpoints organizados por recurso.
- Autenticación y autorización mediante Spring Security.
- Conexión remota a base de datos MySQL.
- Arquitectura escalable y modular.

## 🛠️ Tecnologías utilizadas
- **Java**  
- **Spring Boot**  
- **Spring Security**  
- **MySQL**  
- **JPA / Hibernate**

## 🚀 Ejecución
1. Clonar el repositorio  
   ```bash
   git clone https://github.com/tu-usuario/hotel-management-api.git
2. Configurar el archivo application.properties con tus credenciales de MySQL.
3. Ejecutar la aplicación desde tu IDE o con:
    ```bash
   mvn spring-boot:run

## 📡 Endpoints principales
| Recurso      | Método | Endpoint            | Descripción                       |
| ------------ | ------ | ------------------- | --------------------------------- |
| Clientes     | GET    | `/api/clientes`     | Obtiene todos los clientes        |
| Clientes     | POST   | `/api/clientes`     | Crea un nuevo cliente             |
| Reservas     | GET    | `/api/reservas`     | Lista todas las reservas          |
| Habitaciones | GET    | `/api/habitaciones` | Consulta habitaciones disponibles |
| Empleados    | GET    | `/api/empleados`    | Obtiene el listado de empleados   |
| Facturación  | POST   | `/api/facturas`     | Genera una nueva factura          |

## 🔒 Seguridad
La API utiliza Spring Security para la autenticación y autorización de usuarios.
El acceso a los endpoints está protegido mediante roles y tokens de sesión.

## 👥 Integrantes
[EmiSalias]
[ManuJurado]
[Lisandstone]
[joacom7]

## 📄 Licencia
Este proyecto fue desarrollado con fines educativos en el marco de la formación en Programación y Desarrollo de Software.
Puede ser utilizado como referencia para proyectos académicos o personales.
