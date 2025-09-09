# Repositório Atividade Boas Práticas GitHub

## 🎯 Descrição do desafio 

O desafio consiste em desenvolver um *Sistema de Abertura de Chamados* nas plataformas *desktop, mobile e web, integrado com **Inteligência Artificial gratuita*.  O sistema deve permitir que os usuários abram, acompanhem e encerrem chamados de forma simples, além de oferecer suporte automatizado através de IA.  

Esse projeto busca *otimizar o atendimento interno* de empresas, *reduzir tempo de resposta* e *centralizar a comunicação* entre equipe e cliente.
 
## 📋 Backlog do Produto

| Rank | Prioridade | User Story                               | Sprint | Entrega Resumida                 |
|------|------------|-----------------------------------------|--------|---------------------------------|
| 1    | Alta       | Abrir chamado no sistema                 | 1      | Tela de abertura de chamados    |
| 2    | Alta       | Visualizar lista de chamados             | 2      | Listagem de chamados            |
| 3    | Média      | Editar ou atualizar um chamado existente| 3      | Edição de chamados              |
| 4    | Média      | Gerar relatório de chamados              | 4      | Relatórios e exportação         |
| 5    | Baixa      | Integração com IA                        | 5      | Integração com IA               |

## 🚀 Evolução do Projeto

| Sprint | Período       | Evolução (progresso)       | Entrega (Resumo)                  |
|--------|---------------|----------------------------|----------------------------------|
| 1      | 01/09 - 15/09 | ███░░░░░░░░ 30%           | Tela de abertura de chamados     |
| 2      | 16/09 - 30/09 | █░░░░░░░░░░ 10%           | Listagem de chamados             |
| 3      | 01/10 - 15/10 | ██░░░░░░░░░ 20%           | Edição de chamados               |
| 4      | 16/10 - 31/10 | █░░░░░░░░░░ 10%           | Relatórios e exportação          |
| 5      | 01/11 - 15/11 | ██░░░░░░░░░ 20%           | Integração com IA                |

## 📆 Tabela das Sprints

| Sprint | Período da Sprint | Resumo da Sprint                                | Link Vídeo        | Link Documentação   |
|--------|-----------------|------------------------------------------------|-----------------|------------------|
| 1      | 01/09 - 15/09    | Tela de abertura de chamados e backend básico | [Vídeo Sprint 1](#) | [Doc Sprint 1](#) |
| 2      | 16/09 - 30/09    | Tela de listagem de chamados e filtros por status | [Vídeo Sprint 2](#) | [Doc Sprint 2](#) |
| 3      | 01/10 - 15/10    | Funcionalidade de edição e atualização de chamados | [Vídeo Sprint 3](#) | [Doc Sprint 3](#) |
| 4      | 16/10 - 31/10    | Relatórios básicos e exportação em PDF/Excel  | [Vídeo Sprint 4](#) | [Doc Sprint 4](#) |
| 5      | 01/11 - 15/11    | Integração com IA e sugestões automáticas     | [Vídeo Sprint 5](#) | [Doc Sprint 5](#) |

## 💻 Tecnologias Utilizadas  

<br>

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white) ![Visual Studio Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![Trello](https://img.shields.io/badge/Trello-0079BF?style=for-the-badge&logo=trello&logoColor=white) ![Astah](https://img.shields.io/badge/Astah-3776AB?style=for-the-badge&logo=astah&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-3776AB?style=for-the-badge&logo=figma&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) 

## 🏗️ Estrutura do Projeto

/chamados-app  
│  
├── /backend/       # Servidor, APIs e integração com banco de dados  
├── /frontend/      # Aplicação web  
├── /mobile/        # Aplicação mobile  
├── /docs/          # Documentação detalhada  
├── /tests/         # Testes automatizados  
└── README.md       # Documentação principal

### Requisitos Funcionais

*   **RF1:** Gestão de Chamados: Registrar, acompanhar status, listar, atualizar status e registrar soluções.
*   **RF2:** Inteligência Artificial: Analisar, classificar, sugerir soluções, avaliar prioridade, encaminhar chamados e aprender com soluções.
*   **RF3:** Gerenciamento de Usuários: Cadastrar colaboradores, definir hierarquia e notificar sobre novos chamados.
*   **RF4:** Gerar Relatórios: Mostrar chamados dos últimos 5, 7 e 15 dias, quantidade de chamados resolvidos e pendentes.
*   **RF5:** Gerenciar Notificações: Exibir número de notificações e notificar funcionários sobre novos chamados.

### Requisitos Não Funcionais

*   **RNF1:** Desempenho: Resposta rápida mesmo com múltiplos chamados.
*   **RNF2:** Usabilidade: Interface intuitiva e acessível (desktop e mobile).
*   **RNF3:** Conformidade com LGPD: Garantia de privacidade dos dados pessoais.
*   **RNF4:** Disponibilidade: Sistema disponível em horário comercial, com aviso prévio para manutenção.
*   **RNF5:** Segurança: Criptografia de dados e autenticação forte.

```bash
dotnet restore
```


---

### Executar o Projeto
Siga as instruções abaixo para iniciar o backend e o frontend:

#### Backend (C#)
```bash
dotnet run --project ./src/Backend
```

#### Frontend (Node.js / React / Outro)
```bash
npm start
```

---

### 👥 Equipe

| Membro                       | Função          | GitHub                                                                                     | LinkedIn                                                                                   |
|-----------------------------|-----------------|---------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| Maria Luíza Fonseca Amaro   | Product Owner   | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MariaFAmaro01) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maria-luiza-fonseca-amaro-338305279?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)    |
| Felipe Freitas da Rocha     | Scrum Master    | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Felipe-Freitas-Rocha) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/felipefreitasrocha) |
| Ana Beatriz Barni Franco    | Dev | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Anabarni) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/anabeatrizfranco) |
| Gabriel Freitas de Campos   | Dev | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GabrielFreitas2025) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/gabrielfreitascampos) |
| Maio de Almeida Braga       | Dev | [![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/maioAB) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/maiobraga) |
| Nicolas Furtado Rodrigues   | Dev | [![GitHub](https://github.com/Nicolasdev29) | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0e76a8?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/nicolasfurtado) |
