## Modelo de Caso de Teste

Este modelo de **caso de teste** foi criado por mim, **Beatriz Freitas Coura Silva**, e serve como referência para a escrita de testes manuais de forma clara e estruturada.

| Campo                       | Explicação                                                                                          |
| --------------------------- | --------------------------------------------------------------------------------------------------- |
| **ID Local**                | Identificação do caso de teste, usada como referência para o rastreamento. Exemplo: CT-001, CT-002. |
| **Título do Caso de Teste** | Nome simples e objetivo que descreve o que será testado.                                            |
| **Passos para Execução**    | Sequência de passos necessários para reproduzir o teste. Deve ser clara, ordenada e replicável.     |
| **Dados de Teste**          | Informações de entrada usadas durante o teste (ex.: login, senha, CPF).                             |
| **Resultado Esperado**      | O que o sistema deve apresentar quando o teste for executado corretamente.                          |
| **Resultado Obtido**        | O que realmente aconteceu na execução. Preenchido durante a prática.                                |
| **Status do Teste**         | Situação atual do teste: Novo, Executado, Aprovado, Reprovado.                                      |
| **Criticidade**             | Grau de importância do caso de teste: Baixa, Média ou Alta.                                         |

---

# 📝 Exemplo Preenchido

| Campo                       | Valor                                                                                         |
| --------------------------- | --------------------------------------------------------------------------------------------- |
| **ID Local**                | CT-001                                                                                        |
| **Título do Caso de Teste** | Login com credenciais válidas                                                                 |
| **Passos para Execução**    | 1. Acessar a tela de login <br> 2. Digitar usuário e senha válidos <br> 3. Clicar em "Entrar" |
| **Dados de Teste**          | Usuário: [beatriz@example.com](mailto:beatriz@example.com) <br> Senha: 123456                 |
| **Resultado Esperado**      | Usuário deve acessar o painel principal                                                       |
| **Resultado Obtido**        | *A preencher na execução*                                                                     |
| **Status do Teste**         | Novo                                                                                          |
| **Criticidade**             | Alta                                                                                          |

---

📌 Observações:
* Preencha a tabela com mais casos de teste conforme forem sendo planejados. Este documento é seu rascunho inicial antes do registro formal no Azure DevOps ou Jira. 
* Recomendo repetir cada teste **3 vezes** para maior confiabilidade.
* Sempre que possível, execute em **diferentes plataformas e navegadores**.
* Adicione **evidências** (prints, vídeos, logs) como anexos para fortalecer o registro.

