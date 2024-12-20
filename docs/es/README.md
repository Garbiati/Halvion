# Halvion

**Halvion** es una solución moderna e innovadora de **telemedicina** y **teleconsulta**, diseñada para conectar pacientes y profesionales de la salud a través de videoconferencias de manera simple y eficiente.

## 🚀 Objetivo
La plataforma permite:
- **Doctores** realizar consultas remotas con sus pacientes, ofreciendo un servicio de salud accesible y práctico.
- **Pacientes** tener acceso a atención médica de calidad sin salir de casa.

Halvion busca facilitar la interacción entre doctores y pacientes, promoviendo una experiencia fluida, segura y eficaz, incluso de manera remota.

## 🔑 Funcionalidades Principales
1. **Consultas por Video**: Realice consultas médicas por videoconferencia de manera segura y privada.
2. **Gestión de Perfiles**:
   - **Admin**: Administra la plataforma.
   - **HealthCenterAdmin**: Coordina la administración de un centro médico específico.
   - **Doctor**: Profesional de la salud que realiza consultas.
   - **Patient**: Usuario que utiliza la plataforma para programar y participar en consultas.
   - **Operator**: Ayuda en las operaciones de la plataforma.
3. **Agenda de Consultas**: Organice y programe consultas entre pacientes y doctores.
4. **Integración Segura** con Keycloak para autenticación y autorización.

## 🛠️ Tecnologías Utilizadas
- **ASP.NET Core**: Backend robusto y escalable.
- **Keycloak**: Autenticación y autorización centralizada.
- **WebRTC**: Para videollamadas en tiempo real.
- **Angular**: Para el frontend.
- **PostgreSQL**: Base de datos.

## 🌟 Cómo Ejecutar
1. Clone este repositorio:
   ```bash
   git clone https://github.com/garbiati/halvion.git
   cd halvion
   ```
2. Cree un archivo `.env` en la raíz del proyecto con el siguiente contenido:
   ```plaintext
   POSTGRES_USER=halvion
   POSTGRES_PASSWORD=halvion
   POSTGRES_DB=halvion
   KC_DB_USERNAME=halvion
   KC_DB_PASSWORD=halvion
   KEYCLOAK_ADMIN=admin
   KEYCLOAK_ADMIN_PASSWORD=admin
   ```
3. Inicie la aplicación usando Docker Compose:
   ```bash
   docker compose up --build
   ```
4. Acceda a los servicios:
   - **API**: `http://localhost:5000`
   - **Keycloak**: `http://localhost:8080`

## 📖 Próximos Pasos
- Desarrollar un frontend amigable para interactuar con la API.
- Agregar notificaciones y recordatorios para consultas.
- Soporte para múltiples idiomas.

## 🤝 Contribución
¡Contribuciones son bienvenidas! Siéntase libre de abrir issues y pull requests para ayudar a mejorar Halvion.

---

© 2024 Halvion. Todos los derechos reservados.
