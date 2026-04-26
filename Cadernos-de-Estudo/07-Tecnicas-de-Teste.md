## 📖 Caderno 07 - Técnicas de Teste

### Introdução

Quando uma pessoa inicia em QA, é comum testar de forma intuitiva: clicar em botões, preencher campos e verificar se algo quebra.

Isso funciona até certo ponto.

Mas conforme os sistemas crescem, testar “no feeling” deixa lacunas. É aí que entram as **técnicas de teste**.

As técnicas de teste ajudam o QA a **pensar de forma estruturada**, aumentando cobertura, reduzindo esforço desnecessário e encontrando defeitos com mais eficiência.

Segundo o **ISTQB Foundation Level (CTFL)**, técnicas de teste são métodos utilizados para projetar casos de teste com base em critérios definidos.

Em resumo:

> Técnicas de teste ajudam o QA a testar melhor, e não apenas testar mais.

---

### O que são Técnicas de Teste

São abordagens utilizadas para definir:
- o que testar  
- como testar  
- quantos cenários testar  
- quais riscos priorizar  

Elas evitam testes aleatórios e melhoram a qualidade da validação.

---

### Por que usar Técnicas de Teste

Aplicar técnicas ajuda a:
- aumentar cobertura de testes  
- reduzir casos redundantes  
- encontrar defeitos ocultos  
- priorizar cenários críticos  
- economizar tempo de execução  
- testar com lógica e método  

Em times maduros, isso é muito valorizado.

---

## Principais Técnicas de Teste

---

### 1. Particionamento de Equivalência

Essa técnica divide entradas em grupos que devem se comportar da mesma forma.

Ao invés de testar todos os valores possíveis, testamos representantes de cada grupo.

#### 📌 Exemplo

Campo idade aceita valores entre 18 e 60.

Classes possíveis:
- menor que 18 → inválido  
- entre 18 e 60 → válido  
- maior que 60 → inválido  

Casos escolhidos:
- 15  
- 30  
- 70  

#### ✅ Vantagem

Reduz quantidade de testes sem perder qualidade.

---

### 2. Análise de Valor Limite

Erros costumam acontecer nos extremos.

Por isso testamos valores próximos dos limites.

#### 📌 Exemplo

Campo idade aceita de 18 a 60.

Testar:
- 17  
- 18  
- 19  
- 59  
- 60  
- 61  

#### ✅ Vantagem

Excelente para campos numéricos, datas, tamanhos e regras de faixa.

---

### 3. Tabela de Decisão

Usada quando há várias combinações de regras de negócio.

#### 📌 Exemplo

Desconto aplicado se:
- cliente VIP  
- compra acima de R$200

| VIP | Compra > 200 | Desconto |
|-----|--------------|----------|
| Sim | Sim | Sim |
| Sim | Não | Sim |
| Não | Sim | Não |
| Não | Não | Não |

#### ✅ Vantagem

Ótima para sistemas com regras condicionais.

---

### 4. Transição de Estados

Usada quando o sistema muda de status conforme ações.

#### 📌 Exemplo

Pedido pode estar:
- Em aberto  
- Pago  
- Enviado  
- Cancelado  

Teste importante:
- Pedido cancelado pode voltar para pago? (não deveria)

#### ✅ Vantagem

Muito útil em fluxos administrativos, financeiro e e-commerce.

---

### 5. Teste Exploratório

Aqui o QA utiliza conhecimento e experiência para explorar o sistema sem roteiro rígido.

#### 📌 Exemplo

Ao testar login, além do básico, tentar:
- copiar e colar espaços  
- caracteres especiais  
- navegação rápida  
- múltiplos cliques  

#### ✅ Vantagem

Excelente para encontrar bugs inesperados.

---

## Quando usar cada técnica

| Situação | Técnica recomendada |
|--------|---------------------|
| Campo com faixa numérica | Valor Limite |
| Muitos valores parecidos | Particionamento |
| Regras complexas | Tabela de Decisão |
| Sistema com status | Transição de Estados |
| Descoberta de falhas inesperadas | Exploratório |

---

## Exemplo prático no dia a dia QA

Tela de cadastro com campo idade:

Ao invés de testar 100 valores, um QA experiente aplica:
- Particionamento  
- Valor Limite  

Resultado:
- menos esforço  
- mais inteligência  
- maior chance de encontrar falhas

---

## Erros comuns de iniciantes

- Testar só valores “bonitos”  
- Ignorar limites  
- Não testar combinações de regra  
- Fazer dezenas de testes repetidos  
- Não pensar em risco  

---

## Minha visão prática

Quando comecei a estudar QA, parecia que testar era apenas clicar e validar telas.

Com o tempo, fica claro que técnicas de teste transformam o QA em alguém analítico, capaz de testar com critério e não apenas por tentativa e erro.

Isso diferencia muito no mercado.

---

## Ferramentas onde isso aparece

- Casos de teste manuais  
- Testes exploratórios  
- Automação  
- Refinamentos técnicos  
- Planejamento de regressão  

---

### 📚 Materiais de referência

- [DevMedia - Técnicas de modelagem de teste na prática](https://www.devmedia.com.br/tecnicas-de-modelagem-de-teste-na-pratica/31694) 
- [Guru99 - Análise de valor limite e particionamento de equivalência](https://www.guru99.com/pt/equivalence-partitioning-boundary-value-analysis.html)
- [ZapTest - Particionamento de equivalência em testes de software](https://www.zaptest.com/pt-br/particionamento-de-equivalencia-em-testes-de-software-o-que-e-tipos-processo-abordagens-ferramentas-e-muito-mais) :contentReference[oaicite:3]{index=3}  
- [LinkedIn Artigo - Diferença entre Partição de Equivalência e Valor Limite](https://pt.linkedin.com/pulse/diferen%C3%A7a-entre-parti%C3%A7%C3%A3o-de-equival%C3%AAncia-e-valor-limite-kelly-fiochi-zxauf) :contentReference[oaicite:4]{index=4}  
- **ISTQB Foundation Level (CTFL)** - Técnicas de Teste, Projeto de Testes e Cobertura