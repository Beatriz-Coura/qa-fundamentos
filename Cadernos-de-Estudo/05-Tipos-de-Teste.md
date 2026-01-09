## 📖 Caderno 05 - Tipos de Teste

### Introdução

Os **tipos de teste** existem para garantir a qualidade do software sob diferentes perspectivas.  
Cada tipo tem um **objetivo específico** e ajuda o QA a responder perguntas como:

- O sistema funciona como esperado?
- Mudanças quebraram algo que já funcionava?
- O sistema aguenta muitos usuários?
- O usuário consegue usar o sistema com facilidade?

Entender quando e por que usar cada tipo de teste é essencial para um QA.

---

### Testes Funcionais

Os **testes funcionais** validam se o sistema atende aos **requisitos funcionais**, ou seja, se ele faz o que foi definido.

O que validam:
- Regras de negócio
- Fluxos principais
- Funcionalidades visíveis ao usuário

📌 Exemplos:
- Login funciona com credenciais válidas
- Sistema impede cadastro com CPF inválido
- Botão “Salvar” grava as informações corretamente

Pergunta que responde:  
**“Essa funcionalidade está funcionando como deveria?”**

---

### Testes Não Funcionais

Os **testes não funcionais** avaliam características do sistema que não estão ligadas diretamente a funcionalidades.

O que validam:
- Desempenho
- Usabilidade
- Segurança
- Compatibilidade
- Confiabilidade

📌 Exemplos:
- Tempo de resposta da aplicação
- Facilidade de navegação
- Comportamento em diferentes navegadores
- Proteção contra acessos indevidos

Pergunta que responde:  
**“Como o sistema se comporta?”**

---

### Teste de Regressão

O **teste de regressão** garante que mudanças recentes **não quebraram funcionalidades que já funcionavam**.

Quando usar:
- Após correção de bugs
- Após novas funcionalidades
- Antes de uma entrega ou release

📌 Exemplos:
- Após corrigir o login, testar cadastro, recuperação de senha e logout
- Após nova feature, validar fluxos antigos

Pergunta que responde:  
**“O que já funcionava continua funcionando?”**

---

### Teste Smoke

O **teste smoke** é um conjunto rápido de testes básicos para verificar se o sistema está **estável o suficiente para ser testado**.

Características:
- Superficial
- Rápido
- Executado logo após uma nova versão

📌 Exemplos:
- Sistema abre?
- Login funciona?
- Tela principal carrega?

Pergunta que responde:  
**“O sistema está vivo?”**

---

### Teste Sanity

O **teste sanity** é um teste rápido e focado, geralmente executado após uma **correção específica**.

Diferença para o smoke:
- Smoke → valida o sistema como um todo
- Sanity → valida um ponto específico

📌 Exemplos:
- Bug corrigido no login → testar apenas o login
- Ajuste no cálculo → validar apenas o cálculo

Pergunta que responde:  
**“Essa correção específica funcionou?”**

---

### Comparação rápida

| Tipo de Teste | Objetivo principal | Quando usar |
|--------------|-------------------|-------------|
| Funcional | Validar funcionalidades | Durante o desenvolvimento |
| Não Funcional | Avaliar comportamento e qualidade | Conforme necessidade |
| Regressão | Garantir que nada quebrou | Após mudanças |
| Smoke | Verificar estabilidade básica | Após nova build |
| Sanity | Validar correção pontual | Após bug fix |

---

### 🎯 Conclusão

Nenhum tipo de teste funciona sozinho.  
Um bom QA sabe **combinar diferentes tipos de teste** de acordo com o contexto, tempo e risco do projeto.

O objetivo não é testar tudo, mas **testar o que importa**.

---

### 📚 Materiais de referência

- [Principais tipos de teste de software - artigo DIO](https://www.dio.me/articles/principais-tipos-de-teste-de-software)
- [O que é teste de software? Tipos e importância - Guru99](https://www.guru99.com/pt/software-testing-introduction-importance.html)
-  **ISTQB Foundation Level (CTFL)** - Tipos e níveis de teste  
