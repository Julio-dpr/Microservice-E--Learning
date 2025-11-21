Sistema de cursos (google cloud)
📝 Descripción RESUMIDA 
MODULO 1
Este proyecto tiene como objetivo construir una plataforma de aprendizaje en línea basada en microservicios, que permita la gestión de cursos, usuarios, inscripciones y otros módulos relacionados a la educación digital.
Se busca escalabilidad, modularidad y facilidad de despliegue en entornos distribuidos
Requerimientos funcionales

Gestión de Recursos

Crear, editar, eliminar y listar cursos

Asignar categorías, niveles y etiquetas a cada curso

Gestión de usuarios

Registro y autenticación de estudiantes y docentes

Perfil de usuario con historial de cursos

Los estudiantes pueden inscribirse en cursos disponibles

Validación de cupos y disponibilidad

Microservicios independientes

Servicio de usuarios

Servicio de cursos

Servicio de inscripciones

Servicio de notificaciones (ej: recordatorios por email)
2da implementacion

API RESTFULL

Endpoints documentados para cada servicio

Comunicación entre microservicios vía HTTP/JSON (o gRPC más adelante)

Cada microservicio maneja su propia base de datos

🔒 Requerimientos no funcionales

Escalabilidad: los microservicios deben poder desplegarse y escalarse de manera independiente.

Seguridad: autenticación y autorización con JWT u OAuth2

Disponibilidad: sistema tolerante a fallos con posibilidad de orquestación (Docker/Kubernetes).

Mantenibilidad: código organizado, modular y con documentación clara

Portabilidad: cada microservicio debe correr en contenedores para fácil despliegue.

Monitoreo y logs: integración futura con herramientas de observabilidad (Prometheus, Grafana, ELK)

📦 Tecnologías a usar (mínimos requerimientos)
Backend: Python (FastAPI o Django Rest Framework)

Base de datos: MySQL/PostgreSQL (según microservicio)

Mensajería/colas (futuro): RabbitMQ o Kafka.

Contenedores: Docker.
Gestión de repositorios: Git + GitHub.

📦 Tecnologías a usar (mínimas)

Backend: Python (FastAPI o Django Rest Framework).

Base de datos: MySQL/PostgreSQL (según microservicio)

Mensajería/colas (futuro): RabbitMQ o Kafka.

Contenedores: Docker.

Gestión de repositorios: Git + GitHub.
Creacion de diferentes apartados en figma
IMAGEN 


<img width="625" height="273" alt="image" src="https://github.com/user-attachments/assets/aa0861e9-c10c-47e9-bcf7-f1298d705cc3" />

CONFLICTOS GENERADOS

<img width="882" height="456" alt="image" src="https://github.com/user-attachments/assets/f278da02-d6e8-4ae6-bdde-56f0465cc4b5" />
<img width="887" height="409" alt="image" src="https://github.com/user-attachments/assets/98273c56-9f06-4602-8bc7-858f84607204" />




