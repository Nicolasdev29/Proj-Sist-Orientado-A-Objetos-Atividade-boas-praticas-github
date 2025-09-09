# Como Contribuir

Fico feliz que você esteja interessado em contribuir para este projeto! Para garantir um processo de colaboração eficiente e organizado, por favor, siga as diretrizes abaixo:

## 1. Relatar Bugs e Sugerir Melhorias

*   Antes de abrir uma nova issue, por favor, verifique se uma similar já não existe.
*   Ao relatar um bug, inclua o máximo de detalhes possível: passos para reproduzir, comportamento esperado, comportamento atual e, se possível, capturas de tela ou logs de erro.
*   Ao sugerir uma melhoria ou nova funcionalidade, descreva claramente a proposta e os benefícios que ela traria.

## 2. Processo de Contribuição de Código

1.  **Faça um Fork** do repositório para sua conta pessoal do GitHub.
2.  **Clone** o seu fork para sua máquina local:
    ```bash
    git clone https://github.com/SEU_USUARIO/meu_repositorio_individual.git
    ```
3.  **Crie uma Nova Branch** para sua feature ou correção. Use nomes descritivos, como `feature/nova-funcionalidade` ou `bugfix/correcao-erro-x`.
    ```bash
    git checkout -b feature/sua-feature
    ```
4.  **Faça suas Alterações** no código.
5.  **Commits:** Siga o padrão de mensagens de commit descrito no `README.md` (`<tipo>(<id_demanda>): <descrição>`). Faça commits pequenos e atômicos.
    ```bash
    git commit -m "feat(ISSUE-123): Adiciona nova funcionalidade de busca"
    ```
6.  **Envie suas Alterações** para o seu fork:
    ```bash
    git push origin feature/sua-feature
    ```
7.  **Abra um Pull Request (PR)** para a branch `main` do repositório original.
    *   No título do PR, use o mesmo padrão de commit.
    *   Na descrição do PR, explique detalhadamente as alterações, o problema que resolve (se for um bug) ou a funcionalidade que adiciona. Inclua cenários de teste, se aplicável.

## 3. Padrão de Código

*   Mantenha o código limpo, legível e bem comentado.
*   Siga as convenções de estilo de código existentes no projeto.

## 4. Revisão de Código

*   Seu Pull Request será revisado pela equipe (ou por você mesmo, em um contexto individual de aprendizado).
*   Esteja aberto a feedback e disposto a fazer as alterações solicitadas.

Obrigado por sua contribuição!

