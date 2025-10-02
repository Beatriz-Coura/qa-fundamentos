## 📖 Diferença entre Casos de Teste x Tipos de Testes

### O que é um **Caso de Teste**

Um **caso de teste** é como um **roteiro detalhado** que descreve os passos que o testador deve seguir para validar se uma funcionalidade do sistema funciona corretamente.

* Ele é **específico**.
* Tem começo, meio e fim.
* É **executável**.

📌 Estrutura comum de um caso de teste:

* **Identificador** (CT-001)
* **Pré-condições** (o que precisa estar pronto antes do teste)
* **Passos de execução** (ações que o testador deve seguir)
* **Dados de entrada**
* **Resultado esperado**
* **Resultado obtido** (preenchido durante o teste)

👉 Exemplo:

* **CT-001 – Login com dados válidos**

  * Pré-condição: Usuário cadastrado no sistema
  * Passo 1: Acessar a tela de login
  * Passo 2: Informar usuário e senha válidos
  * Resultado esperado: Usuário acessa o painel principal

---

### 🔹 O que é um **Tipo de Teste**

Um **tipo de teste** é uma **categoria de avaliação** usada para verificar diferentes aspectos do software.

* Ele é **mais genérico**.
* Classifica os testes de acordo com o **objetivo** (funcionalidade, segurança, desempenho etc.).

📌 Exemplos de tipos de teste:

* **Teste Funcional** → valida se o sistema faz o que deveria.
* **Teste de Segurança** → identifica falhas que podem comprometer o sistema.
* **Teste de Usabilidade** → verifica se o sistema é fácil de usar.
* **Teste de Desempenho** → avalia tempo de resposta, carga e escalabilidade.

---

### ⚖️ Comparação lado a lado

| **Aspecto**               | **Caso de Teste**                                  | **Tipo de Teste**                            |
| ------------------------- | -------------------------------------------------- | -------------------------------------------- |
| **Definição**             | Roteiro específico para validar uma funcionalidade | Categoria de avaliação do software           |
| **Nível de detalhe**      | Muito detalhado (passo a passo)                    | Mais geral e abrangente                      |
| **Exemplo**               | CT-001: Login com dados válidos                    | Teste Funcional                              |
| **Pergunta que responde** | "Este cenário funciona?"                           | "Qual aspecto do sistema estamos avaliando?" |

---

### 🎯 Analogia para fixar

* **Tipos de Teste** → são como **disciplinas escolares** (Matemática, Português, História).
* **Casos de Teste** → são como **exercícios/provas** dentro de cada disciplina.

Ou seja: o **tipo de teste** define o "campo de estudo", e os **casos de teste** são as atividades práticas que colocam à prova esse conhecimento.
