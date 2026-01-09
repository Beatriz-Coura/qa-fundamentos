## 📖 Caderno 04 - Tipos de Teste, Cenários e Casos de Teste

### Introdução

No dia a dia de QA, é muito comum ouvir termos como **tipo de teste**, **cenário de teste** e **caso de teste** sendo usados como se fossem a mesma coisa.  
Mas, segundo o **ISTQB Foundation Level (CTFL)**, cada um desses conceitos tem um papel diferente, e entender essa diferença ajuda muito na organização dos testes e na comunicação com o time.

---

### O que são **Tipos de Teste**

Um **tipo de teste** é uma **classificação** usada para definir **o que queremos avaliar no software**.

Ele responde à pergunta:

> **“Qual aspecto do sistema estamos testando?”**

Os tipos de teste são mais **abstratos** e ajudam a montar a **estratégia de testes**.

#### Exemplos de tipos de teste

- **Teste Funcional** → valida se a funcionalidade atende aos requisitos
- **Teste de Regressão** → verifica se algo que já funcionava quebrou
- **Teste de Usabilidade** → avalia facilidade de uso e experiência do usuário
- **Teste de Performance** → mede tempo de resposta e estabilidade
- **Teste de Segurança** → identifica vulnerabilidades

📌 Um tipo de teste **não descreve passos**, apenas define o foco da validação.

---

### O que são **Cenários de Teste**

Um **cenário de teste** descreve **uma situação de uso do sistema**, de forma mais ampla e menos detalhada.

Ele responde à pergunta:

> **“Em que situação o usuário pode usar essa funcionalidade?”**

#### Características do cenário de teste

- Mais **alto nível**
- Focado no **comportamento**
- Pode gerar **vários casos de teste**

#### Exemplo de cenário

**Cenário: Usuário realiza login no sistema**

Esse cenário pode abranger:
- login com dados válidos
- login com senha inválida
- login com usuário inexistente
- tentativa de login sem preencher campos

💡 O cenário ajuda o QA a **pensar como usuário**, antes de entrar nos detalhes técnicos.

---

### O que é um **Caso de Teste**

Um **caso de teste** é um **roteiro detalhado e executável**, que descreve exatamente **como testar** uma funcionalidade.

Ele responde à pergunta:

> **“Quais passos eu sigo para validar esse cenário?”**

#### Estrutura comum de um caso de teste

- **Identificador** (ex.: CT-001)
- **Pré-condições**
- **Passos de execução**
- **Dados de entrada**
- **Resultado esperado**
- **Resultado obtido** (preenchido durante a execução)

#### Exemplo de caso de teste

**CT-001 - Login com dados válidos**

- Pré-condição: Usuário cadastrado no sistema
- Passo 1: Acessar a tela de login
- Passo 2: Informar usuário e senha válidos
- Passo 3: Clicar em “Entrar”
- Resultado esperado: Usuário acessa o painel principal

📌 Diferente do cenário, o caso de teste **não deixa espaço para interpretação**.

---

### Relação entre Tipo de Teste, Cenário e Caso de Teste

Esses três conceitos se complementam.

| Nível | Conceito | Pergunta que responde |
|-----|--------|-----------------------|
| Estratégico | **Tipo de Teste** | O que queremos validar? |
| Tático | **Cenário de Teste** | Em que situação o sistema será usado? |
| Operacional | **Caso de Teste** | Como executar o teste passo a passo? |

#### Exemplo prático

- **Tipo de Teste**: Teste Funcional  
- **Cenário**: Usuário realiza login no sistema  
- **Casos de Teste**:
  - CT-001 - Login com dados válidos
  - CT-002 - Login com senha inválida
  - CT-003 - Login com campos vazios

---

### 🎯 Analogia para fixar

- **Tipos de Teste** → são como o **objetivo do treino** (força, resistência, alongamento)
- **Cenários de Teste** → são como os **exercícios planejados**
- **Casos de Teste** → são as **séries e repetições detalhadas**

Ou seja:
> o tipo define o foco, o cenário define a situação e o caso de teste define a execução.

---

### 📚 Materiais de referência

- [Tipos de Testes de Software - Atlassian](https://www.atlassian.com/br/continuous-delivery/software-testing/types-of-software-testing)  
- [Entenda a diferença entre Caso de Teste e Cenário de Teste - DIO](https://www.dio.me/articles/entenda-a-diferenca-caso-de-teste-cenario-de-teste)  
-  **ISTQB Foundation Level (CTFL)** - conceitos de tipos de teste e níveis de teste
