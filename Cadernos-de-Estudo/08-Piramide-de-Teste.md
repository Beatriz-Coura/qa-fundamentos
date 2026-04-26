## 📖 Caderno 08 - Pirâmide de Testes

### Introdução

Quando uma aplicação cresce, surge uma dúvida comum:

> Quais testes devemos automatizar primeiro?

Se tudo virar teste manual, o processo fica lento.  
Se tudo virar teste automatizado de interface, o custo de manutenção explode.

Para resolver isso, surgiu o conceito da **Pirâmide de Testes**, muito utilizado em times ágeis e recomendado como estratégia moderna de qualidade.

Ela ajuda a equilibrar:
- velocidade  
- custo  
- cobertura  
- confiabilidade  
- manutenção

---

### O que é a Pirâmide de Testes

A Pirâmide de Testes representa **como distribuir os testes automatizados em camadas**.

A ideia principal é:
- **Base larga:** muitos testes rápidos e baratos  
- **Meio moderado:** quantidade média de testes integrados  
- **Topo pequeno:** poucos testes lentos e caros

---

<img width="512" height="410" alt="imagem piramide de teste" src="https://github.com/user-attachments/assets/3f3a76b0-2817-4426-be04-8680a03d62fc" />

---

## Estrutura da Pirâmide

### 1. Base - Testes Unitários

São testes feitos em pequenas partes do sistema, normalmente funções, métodos ou classes.

#### 📌 Exemplos

- cálculo de desconto  
- validação de CPF  
- regra de juros  
- formatação de datas

#### ✅ Vantagens

- extremamente rápidos  
- baratos de executar  
- fáceis de localizar falhas  
- rodam a cada commit

#### 💡 Visão prática

Quanto mais testes unitários saudáveis, menos bugs chegam nas camadas superiores.

---

### 2. Meio - Testes de Integração

Validam a comunicação entre módulos.

#### 📌 Exemplos

- API + banco de dados  
- backend + fila  
- serviço de autenticação + sistema principal  
- front consumindo API

#### ✅ Vantagens

- pegam falhas reais entre componentes  
- validam contratos e integrações  
- importantes em microsserviços

---

### 3. Topo - Testes End-to-End (E2E / UI)

Simulam o comportamento do usuário do início ao fim.

#### 📌 Exemplos

- login + compra + pagamento  
- cadastro + confirmação por e-mail  
- emissão de proposta + aprovação

#### ✅ Vantagens

- validam fluxo real do negócio  
- alta confiança funcional

#### ❌ Desvantagens

- lentos  
- frágeis  
- caros de manter  
- quebram por pequenas mudanças visuais

---

## Como interpretar a Pirâmide

| Camada | Quantidade | Velocidade | Custo | Manutenção |
|--------|------------|------------|-------|------------|
| Unitário | Alta | Muito alta | Baixo | Baixa |
| Integração | Média | Média | Médio | Média |
| E2E/UI | Baixa | Baixa | Alto | Alta |

---

## Erro comum: Sorvete de Casquinha

Quando o time faz quase tudo em UI/E2E e pouco teste unitário.

Resultado:
- suíte lenta  
- manutenção cara  
- muitos falsos negativos  
- pipeline instável

Esse antipadrão é conhecido como:

> **Ice Cream Cone Anti-pattern**

---

## Minha visão prática como QA

Muitos iniciantes pensam que automação = Selenium clicando em tela.

Mas times maduros entendem que:

> qualidade começa na base, não no topo.

Se a regra de negócio quebra no teste unitário, ela nem deveria chegar no teste de interface.

---

## Onde o QA entra nisso

Mesmo quando desenvolvedores criam testes unitários, o QA pode contribuir com:

- sugestão de cenários críticos  
- análise de riscos  
- priorização de integrações importantes  
- definição de fluxos E2E prioritários  
- melhoria da estratégia de testes

QA moderno participa da estratégia, não só da execução.

---

## Exemplo realista de e-commerce

### Unitários

- cálculo de frete  
- cupom de desconto  
- estoque mínimo

### Integração

- pedido salvo no banco  
- comunicação com gateway de pagamento

### E2E

- cliente compra produto com cartão válido

---

## Ferramentas comuns

### Testes Unitários

- JUnit  
- NUnit  
- xUnit  
- Jest

### Testes de Integração

- Postman  
- Rest Assured  
- Supertest

### Testes E2E

- Selenium  
- Cypress  
- Playwright

---

## Aplicação no Portfólio

Mostrar entendimento sobre Pirâmide de Testes transmite maturidade profissional.

Mesmo como QA Júnior, isso demonstra visão de:
- arquitetura de testes  
- automação inteligente  
- custo x benefício  
- qualidade escalável

---

### 📚 Materiais de referência

- [Atlassian Brasil - Tipos de Testes de Software](https://www.atlassian.com/br/continuous-delivery/software-testing/types-of-software-testing)  
- [Microsoft Learn Brasil - Introdução aos Testes no Azure DevOps](https://learn.microsoft.com/pt-br/azure/devops/test/?view=azure-devops)
- [Alura - Qualidade de Software e Automação de Testes](https://www.alura.com.br/artigos/quality-assurance)  
- **ISTQB Foundation Level (CTFL)** - Estratégia de Testes, Níveis de Teste e Automação
