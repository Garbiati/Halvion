# Halvion

**Halvion** is a modern and innovative solution for **telemedicine** and **teleconsultation**, designed to connect patients and healthcare professionals through video conferencing in a simple and efficient way.

## 🚀 Objective
The platform allows:
- **Doctors** to conduct remote consultations with their patients, offering accessible and practical healthcare services.
- **Patients** to receive quality medical care without leaving their homes.

Halvion aims to facilitate interaction between doctors and patients, promoting a smooth, secure, and effective experience, even remotely.

## 🔑 Key Features
1. **Video Consultations**: Conduct medical consultations via secure and private video conferencing.
2. **Profile Management**:
   - **Admin**: Manages the platform.
   - **HealthCenterAdmin**: Coordinates the administration of a specific health center.
   - **Doctor**: Healthcare professional conducting consultations.
   - **Patient**: User scheduling and participating in consultations.
   - **Operator**: Assists in platform operations.
3. **Appointment Scheduling**: Organize and schedule appointments between patients and doctors.
4. **Secure Integration** with Keycloak for authentication and authorization.

## 🛠️ Technologies Used
- **ASP.NET Core**: Robust and scalable backend.
- **Keycloak**: Centralized authentication and authorization.
- **WebRTC**: For real-time video calls.
- **Angular**: For the frontend.
- **PostgreSQL**: Database.

## 🌟 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/garbiati/halvion.git
   cd halvion
   ```
2. Create a `.env` file in the project root with the following content:
   ```plaintext
   POSTGRES_USER=halvion
   POSTGRES_PASSWORD=halvion
   POSTGRES_DB=halvion
   KC_DB_USERNAME=halvion
   KC_DB_PASSWORD=halvion
   KEYCLOAK_ADMIN=admin
   KEYCLOAK_ADMIN_PASSWORD=admin
   ```
3. Start the application using Docker Compose:
   ```bash
   docker compose up --build
   ```
4. Access the services:
   - **API**: `http://localhost:5000`
   - **Keycloak**: `http://localhost:8080`

## 📖 Next Steps
- Develop a user-friendly frontend to interact with the API.
- Add notifications and reminders for consultations.
- Support for multiple languages.

## 🤝 Contribution
Contributions are welcome! Feel free to open issues and pull requests to help improve Halvion.

---

© 2024 Halvion. All rights reserved.
