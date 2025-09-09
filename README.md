# Meu Repositório Individual - PIM 3.0

## Visão Geral do Projeto

Este repositório individual é parte do projeto PIM 3.0 (Projeto Integrado Multidisciplinar) da Universidade Paulista, curso de Análise e Desenvolvimento de Sistemas. O objetivo principal é demonstrar a aplicação de boas práticas de desenvolvimento e versionamento de código utilizando Git e GitHub, conforme as diretrizes fornecidas no 'Guia do GitHub'.

O projeto PIM 3.0, intitulado **SmartDesk**, visa otimizar o atendimento de chamados em empresas de médio porte, promovendo agilidade, organização e eficiência nos processos de suporte técnico. Este repositório reflete minha contribuição individual e a aplicação das metodologias aprendidas.

## 🚀 Requisitos Funcionais e Não Funcionais (SmartDesk)

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

## 📚 Documentação e Boas Práticas

Este repositório segue as boas práticas de documentação e versionamento de código conforme o 'Guia do GitHub' fornecido. Abaixo, detalho como essas práticas são aplicadas:

### 1. Padrão de Mensagens de Commit

Adoto o seguinte padrão para as mensagens de commit, visando clareza e rastreabilidade:

`<tipo>(<id_demanda>): <descrição da entrega feita no commit>`

**Tipos de Commit:**

*   `feat`: Novas funcionalidades ou recursos.
*   `fix`: Correções de bugs.
*   `docs`: Alterações na documentação.
*   `style`: Mudanças de formatação, sem alteração de lógica.
*   `refactor`: Refatoração de código, sem mudança de funcionalidade.
*   `test`: Adição ou modificação de testes.
*   `chore`: Atualizações menores, como configurações de build ou dependências.

**Exemplos:**

*   `feat(SMART-001): Implementa módulo de autenticação de usuários`
*   `fix(SMART-002): Corrige erro de exibição na listagem de chamados`
*   `docs: Atualiza seção de instalação no README`

### 2. Estratégia de Branch

Para este repositório individual, utilizo uma variação simplificada do **GitHub Flow**, adaptada para um contexto de desenvolvimento único. A estratégia é a seguinte:

*   A branch `main` é sempre a versão estável e pronta para uso.
*   Para cada nova funcionalidade, correção de bug ou melhoria significativa, uma nova branch é criada a partir da `main`.
    *   **Nomenclatura:** `feature/<nome-da-feature>`, `bugfix/<nome-do-bug>`, `docs/<nome-da-doc>`.
*   Todo o desenvolvimento ocorre na branch específica.
*   Após a conclusão e testes, um Pull Request (PR) é aberto para a `main`.
*   O merge para a `main` só ocorre após a revisão e aprovação (simulada, neste caso, por uma auto-revisão rigorosa).

Esta abordagem garante que a `main` permaneça sempre limpa e funcional, enquanto o desenvolvimento de novas funcionalidades é isolado e organizado.

### 3. Boas Práticas do Git Aplicadas

*   **`.gitignore`:** Um arquivo `.gitignore` foi configurado para ignorar arquivos temporários, logs, binários, configurações de IDEs e outras pastas irrelevantes para o controle de versão, mantendo o repositório limpo e focado no código-fonte.
*   **Commits Atômicos:** Realizo commits pequenos e focados, cada um abordando uma única alteração lógica. Isso facilita a revisão do histórico e a identificação de problemas.
*   **Mensagens Imperativas:** As mensagens de commit são escritas no imperativo, descrevendo a ação realizada (ex: 'Adiciona', 'Corrige', 'Atualiza').
*   **Evitar Commit Direto na `main`:** Todas as alterações são feitas em branches separadas e integradas via Pull Request, garantindo a integridade da branch principal.
*   **Pull Requests (PRs):** Embora seja um repositório individual, simulo o processo de PR para cada feature/bugfix, descrevendo as alterações e os cenários de teste. Isso serve como um registro detalhado do desenvolvimento.

## 🛠️ Como Contribuir (Exemplo para Futuras Colaborações)

1.  Faça um fork deste repositório.
2.  Crie uma nova branch (`git checkout -b feature/sua-feature`).
3.  Faça suas alterações e commite-as (`git commit -m 'feat: Adiciona sua feature'`).
4.  Envie para o seu fork (`git push origin feature/sua-feature`).
5.  Abra um Pull Request para a branch `main` deste repositório.

## 📄 Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

