# Halvion

**Halvion** é uma solução moderna e inovadora de **telemedicina** e **teleconsulta**, projetada para conectar pacientes e profissionais de saúde através de videoconferências de forma simples e eficiente.

## 🚀 Objetivo
A plataforma permite:
- **Médicos** realizarem consultas remotas com seus pacientes, oferecendo um serviço de saúde acessível e prático.
- **Pacientes** terem acesso a cuidados médicos de qualidade sem sair de casa.

O Halvion busca facilitar a interação entre médicos e pacientes, promovendo uma experiência fluida, segura e eficaz, mesmo à distância.

## 🔑 Funcionalidades Principais
1. **Consultas por Vídeo**: Realize consultas médicas por videoconferência de forma segura e privada.
2. **Gerenciamento de Perfis**:
   - **Admin**: Gerencia a plataforma.
   - **HealthCenterAdmin**: Coordena a administração de um centro médico específico.
   - **Doctor**: Profissional de saúde que realiza as consultas.
   - **Patient**: Usuário que utiliza a plataforma para agendar e participar de consultas.
   - **Operator**: Auxilia nas operações da plataforma.
3. **Agendamento de Consultas**: Organize e agende consultas entre pacientes e médicos.
4. **Integração Segura** com Keycloak para autenticação e autorização.

## 🛠️ Tecnologias Utilizadas
- **ASP.NET Core**: Backend robusto e escalável.
- **Keycloak**: Autenticação e autorização centralizada.
- **WebRTC**: Para videochamadas em tempo real.
- **Angular**: Para o frontend.
- **PostgreSQL**: Banco de dados.

## 🌟 Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/garbiati/halvion.git
   cd halvion
   ```
2. Crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:
   ```plaintext
   POSTGRES_USER=halvion
   POSTGRES_PASSWORD=halvion
   POSTGRES_DB=halvion
   KC_DB_USERNAME=halvion
   KC_DB_PASSWORD=halvion
   KEYCLOAK_ADMIN=admin
   KEYCLOAK_ADMIN_PASSWORD=admin
   ```
3. Inicie a aplicação usando Docker Compose:
   ```bash
   docker compose up --build
   ```
4. Acesse os serviços:
   - **API**: `http://localhost:5000`
   - **Keycloak**: `http://localhost:8080`

## 📖 Próximos Passos
- Desenvolver um frontend amigável para interação com a API.
- Adicionar notificações e lembretes para consultas.
- Suporte a múltiplos idiomas.

## 🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para ajudar a melhorar o Halvion.

---

© 2024 Halvion. Todos os direitos reservados.
