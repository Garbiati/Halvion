# Halvion

**Halvion** é uma solução moderna e inovadora de **telemedicina** e **teleconsulta** projetada para conectar pacientes e profissionais de saúde através de conferências de vídeo de forma simples e eficiente. 

## 🚀 Objetivo
A plataforma permite que:
- **Médicos** realizem consultas remotas com seus pacientes, oferecendo um serviço de saúde acessível e prático.
- **Pacientes** tenham acesso a cuidados médicos de qualidade sem sair de casa.

Halvion busca facilitar a interação entre médicos e pacientes, promovendo uma experiência fluida, segura e eficaz, mesmo à distância.

## 🔑 Funcionalidades Principais
1. **Consultas por Vídeo**: Realize consultas médicas por videoconferência de forma segura e privada.
2. **Gerenciamento de Perfis**:
   - **Admin**: Gerencia a plataforma.
   - **HealthCenterAdmin**: Coordena a administração de um centro médico específico.
   - **Doctor**: Profissional de saúde que realiza as consultas.
   - **Patient**: Usuário que utiliza a plataforma para agendar e participar de consultas.
   - **Operator**: Auxilia nas operações de suporte da plataforma.
3. **Agenda de Consultas**: Organização e agendamento de horários entre pacientes e médicos.
4. **Integração Segura** com Keycloak para autenticação e autorização.

## 🛠️ Tecnologias Utilizadas
- **ASP.NET Core**: Backend robusto e escalável.
- **Keycloak**: Autenticação e autorização centralizada.
- **WebRTC**: Para videochamadas em tempo real.
- **Angular**: Para o frontend.
- **PostgreSQL**: Banco de dados.

## 🌟 Como Usar
1. Clone este repositório:
   ```bash
   git clone https://github.com/garbiati/halvion.git
   cd halvion
   ```
2. Configure as variáveis de ambiente e o Keycloak (detalhes em breve).
3. Inicie o servidor:
   ```bash
   dotnet run
   ```

## 📖 Próximos Passos
- Desenvolvimento de um frontend amigável para interação com a API.
- Adicionar notificações e lembretes de consultas.
- Suporte a múltiplos idiomas.

## 🤝 Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para ajudar a melhorar o Halvion.

---

© 2024 Halvion. Todos os direitos reservados.
