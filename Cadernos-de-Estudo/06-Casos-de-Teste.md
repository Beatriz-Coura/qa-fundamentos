## 📖 Caderno 06 - Casos de Teste

### Introdução

Um dos conhecimentos mais importantes para quem atua com QA Manual é saber **escrever bons casos de teste**.

Muitas pessoas iniciantes enxergam o caso de teste apenas como uma planilha preenchida, mas na prática ele representa **organização, rastreabilidade e pensamento analítico**.

Segundo o **ISTQB Foundation Level (CTFL)**, casos de teste ajudam a transformar condições de teste em verificações objetivas, permitindo validar o sistema de forma estruturada.

Em outras palavras:

> Um bom caso de teste mostra que o QA sabe pensar antes de executar.

---

### O que é um Caso de Teste

Um **caso de teste** é um conjunto documentado de:

- pré-condições  
- passos de execução  
- dados de entrada  
- resultados esperados  

Seu objetivo é validar se determinada funcionalidade do sistema se comporta corretamente.

Ele funciona como um **roteiro de validação**, permitindo que qualquer pessoa do time execute o teste com consistência.

---

### 📌 Exemplo simples

#### CT-001 - Login com credenciais válidas

**Pré-condição:** usuário cadastrado no sistema

**Passos:**

1. Acessar tela de login  
2. Informar usuário válido  
3. Informar senha válida  
4. Clicar em Entrar  

**Resultado esperado:** usuário acessa a área logada.

---

### Por que Casos de Teste são importantes

Casos de teste ajudam a:

- organizar a execução dos testes  
- garantir cobertura funcional  
- evitar esquecimentos  
- facilitar regressões futuras  
- documentar comportamentos esperados  
- permitir rastreabilidade entre requisito e validação  
- padronizar o trabalho entre QAs diferentes  

Em ambientes corporativos, isso é extremamente valorizado.

---

### Estrutura comum de um Caso de Teste

Os campos mais comuns são:

| Campo | Objetivo |
|------|----------|
| ID | Identificação única |
| Título | Nome claro do teste |
| Pré-condição | O que precisa existir antes |
| Passos | Sequência de execução |
| Dados de Teste | Entradas utilizadas |
| Resultado Esperado | O comportamento correto |
| Resultado Obtido | O que realmente aconteceu |
| Status | Aprovado / Reprovado |
| Criticidade | Impacto para negócio |

---

### Boas práticas na escrita de Casos de Teste

#### Seja claro e objetivo

Evite textos vagos.

❌ Testar login normalmente  
✅ Informar usuário válido e senha válida

---

#### Um objetivo principal por teste

Cada caso deve validar uma regra específica.

❌ Login + Logout + Cadastro no mesmo teste  
✅ Um teste para cada fluxo

O próprio Azure Test Plans recomenda separar cenários com fluxos diferentes em casos distintos.

---

#### Títulos profissionais

O nome do caso deve permitir rápida identificação.

❌ Teste tela inicial  
✅ Login com senha inválida

---

#### Passos reproduzíveis

Outra pessoa deve conseguir executar igual.

❌ Fazer login  
✅ Informar usuário e senha

---

#### Resultado esperado mensurável

❌ Sistema funciona  
✅ Usuário é redirecionado para página Products

---

#### Priorize o que é crítico

Nem tudo tem o mesmo impacto.

Alta criticidade:
- Login  
- Pagamento  
- Cadastro  

Média:
- Busca  
- Filtros  

Baixa:
- Ajustes visuais secundários

---

### Erros comuns de iniciantes

- Casos genéricos demais  
- Falta de resultado esperado  
- Muitos objetivos no mesmo teste  
- Passos incompletos  
- Títulos ruins  
- Não atualizar status após execução  

---

### Caso de Teste x Cenário de Teste

#### Cenário de Teste

É uma visão macro.

> Validar autenticação de usuários.

#### Caso de Teste

É a validação detalhada.

- Login com usuário válido  
- Login com senha inválida  
- Login com campos vazios  

Ou seja:

- **Cenário = o que testar**  
- **Caso de teste = como testar**

---

### Ferramentas mais comuns

- **Azure DevOps / Azure Test Plans** - gestão corporativa de testes manuais e rastreabilidade
- **Jira + Xray** - muito utilizado em times ágeis  
- **TestRail** - gestão especializada de testes  
- **Planilhas** - cenários menores ou estudos  
- **Zephyr** - integrado ao Jira  

---

### Aplicação prática no mercado

Um QA que sabe escrever bons casos de teste normalmente demonstra:

- pensamento estruturado  
- boa interpretação de requisitos  
- visão de risco  
- comunicação clara  
- organização profissional  

Por isso, mesmo com automação crescendo, essa habilidade continua essencial.

---

### 📚 Materiais de referência

- [Criar e gerenciar casos de teste manuais - Microsoft Learn](https://learn.microsoft.com/pt-br/azure/devops/test/create-test-cases?view=azure-devops)
- [Azure Test Plans - Microsoft Learn](https://learn.microsoft.com/pt-br/azure/devops/test/overview)
- [Como escrever casos de teste funcionais - Julio de Lima (YouTube)](https://www.youtube.com/watch?v=BMeOV1-senE)
- **ISTQB Foundation Level (CTFL)** - Modelagem de Testes e Produtos de Trabalho
