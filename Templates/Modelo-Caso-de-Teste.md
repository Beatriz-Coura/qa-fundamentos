## Modelo de Caso de Teste

Este modelo de **caso de teste** foi criado por mim, **Beatriz Freitas Coura Silva**, e serve como referência para a escrita de testes manuais de forma clara e estruturada.

| **ID Local** | **Título do Caso de Teste**                 | **Pré-condições**                                           | **Passos para Execução**                        | **Dados de Teste**                       | **Resultado Esperado**                                | **Resultado Obtido**                               | **Status do Teste**                     | **Criticidade**      |
| ------------ | ------------------------------------------- | ----------------------------------------------------------- | ----------------------------------------------- | ---------------------------------------- | ----------------------------------------------------- | -------------------------------------------------- | --------------------------------------- | -------------------- |
| CT-001       | Descreva de forma curta o objetivo do teste | Condições que precisam estar configuradas antes da execução | Passos claros e numerados para realizar o teste | Entradas usadas (ex.: login, senha, CPF) | O que o sistema deve retornar se tudo estiver correto | O que aconteceu de fato (preenchido após execução) | Novo / Executado / Aprovado / Reprovado | Baixa / Média / Alta |

## 📌 Explicação de cada campo

* **ID Local** → Identificador único do caso de teste (ex.: CT-001). Facilita o rastreamento.
* **Título do Caso de Teste** → Nome simples e objetivo que descreve a finalidade do teste.
* **Pré-condições** → Situações necessárias antes da execução (ex.: usuário já cadastrado).
* **Passos para Execução** → Lista numerada de ações que o testador deve seguir. Deve ser clara e replicável.
* **Dados de Teste** → Valores de entrada a serem utilizados no teste (ex.: login, senha, CPF).
* **Resultado Esperado** → O comportamento correto do sistema.
* **Resultado Obtido** → O que realmente ocorreu (preenchido após execução).
* **Status do Teste** → Indica a situação atual do caso: Novo, Executado, Aprovado, Reprovado.
* **Criticidade** → Define a importância do teste (Baixa, Média ou Alta), de acordo com o impacto no negócio.

---

## Exemplo Preenchido


| **ID Local** | **Título do Caso de Teste**   | **Pré-condições**             | **Passos para Execução**                                                                             | **Dados de Teste**                                                            | **Resultado Esperado**                                         | **Resultado Obtido** | **Status do Teste** | **Criticidade** |
| ------------ | ----------------------------- | ----------------------------- | ---------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------- | -------------------------------------------------------------- | -------------------- | ------------------- | --------------- |
| CT-001       | Login com credenciais válidas | Usuário cadastrado no sistema | 1. Acessar tela de login <br> 2. Inserir usuário e senha válidos <br> 3. Clicar em "Entrar"          | Usuário: [beatriz@example.com](mailto:beatriz@example.com) <br> Senha: 123456 | Usuário acessa painel principal                                | *A preencher*        | Novo                | Alta            |
| CT-002       | Login com senha inválida      | Usuário cadastrado no sistema | 1. Acessar tela de login <br> 2. Inserir usuário válido e senha incorreta <br> 3. Clicar em "Entrar" | Usuário: [beatriz@example.com](mailto:beatriz@example.com) <br> Senha: 999999 | Sistema exibe mensagem "Senha incorreta"                       | *A preencher*        | Novo                | Alta            |

---

📌 Observações:
* Preencha a tabela com mais casos de teste conforme forem sendo planejados. Este documento é seu rascunho inicial antes do registro formal no Azure DevOps ou Jira. 
* Recomendo repetir cada teste **3 vezes** para maior confiabilidade.
* Sempre que possível, execute em **diferentes plataformas e navegadores**.
* Adicione **evidências** (prints, vídeos, logs) como anexos para fortalecer o registro.