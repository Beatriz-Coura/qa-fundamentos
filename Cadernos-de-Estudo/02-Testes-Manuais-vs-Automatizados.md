## 📖 Caderno 02 - Testes Manuais vs Testes Automatizados

### Introdução
Uma das primeiras decisões que um QA precisa aprender a tomar é:  
**quando testar manualmente e quando automatizar**.

No início da carreira, é comum associar automação a “nível avançado” e testes manuais a algo simples.  
Na prática (e como o CTFL reforça), **ambos são complementares** e têm papéis diferentes na estratégia de testes.

---

### O que são Testes Manuais
Os **testes manuais** são aqueles em que o QA executa os cenários de teste **diretamente**, sem o uso de scripts ou ferramentas de automação.

Eles envolvem:
- seguir **casos de teste previamente definidos**
- observar o comportamento do sistema
- analisar se o software atende às expectativas do usuário

Esse tipo de teste é muito importante para validar **usabilidade**, **experiência do usuário (UX)** e situações onde o olhar humano faz diferença.

#### 📌 Exemplos práticos

- Acessar a tela de login e tentar entrar com credenciais corretas e incorretas  
- Verificar se o botão “Cadastrar” direciona para a tela correta  
- Explorar o sistema como um usuário real, buscando comportamentos inesperados  

#### ✅ Vantagens dos testes manuais

- Flexibilidade para explorar cenários não previstos  
- Não exigem conhecimento em programação  
- Menor custo inicial  

#### ❌ Desvantagens dos testes manuais

- Execução mais lenta  
- Maior chance de erro humano  
- Difíceis de repetir em grande escala  

---

### O que são Testes Automatizados

Os **testes automatizados** utilizam scripts, códigos ou ferramentas para executar cenários de teste de forma automática.

Eles são indicados principalmente para:
- testes repetitivos  
- testes de regressão  
- validações que precisam ser executadas com frequência  

Segundo o **CTFL**, a automação ajuda a aumentar a **eficiência** dos testes, mas não substitui totalmente o teste manual.

#### 📌 Exemplos práticos

- Utilizar Selenium para validar login em diferentes navegadores  
- Automatizar testes de API com Postman/Newman em uma pipeline CI/CD  
- Executar testes de performance com JMeter  

#### ✅ Vantagens dos testes automatizados

- Execução rápida e consistente  
- Possibilidade de testar em larga escala  
- Integração com pipelines de entrega contínua (CI/CD)  

#### ❌ Desvantagens dos testes automatizados

- Alto custo inicial de implementação  
- Necessidade de conhecimento técnico  
- Manutenção constante conforme o sistema evolui  

---

### Quando usar testes manuais e quando usar testes automatizados?

#### Testes manuais são mais indicados quando:

- O sistema ainda está em fase inicial ou instável  
- É necessário avaliar **usabilidade e experiência do usuário**  
- O objetivo é realizar **testes exploratórios**  

#### Testes automatizados são mais indicados quando:

- O sistema já está mais estável  
- Existe um grande volume de testes repetitivos (como regressão)  
- Há necessidade de rapidez e escala  

A principal conclusão (reforçada pelo CTFL) é que **não existe escolha certa ou errada**, e sim **uso estratégico**.

- Testes manuais ajudam a encontrar problemas que scripts não veem  
- Testes automatizados ajudam a garantir consistência e agilidade  

---

### Ferramentas mais comuns

#### Ferramentas para testes manuais

- **Jira / Azure DevOps** – gestão de casos de teste e bugs  
- **TestRail** – documentação e organização de testes  
- **Trello** – gestão simples de tarefas  

#### Ferramentas para testes automatizados

- **Selenium** – automação de testes web  
- **Cypress** – automação moderna de aplicações frontend  
- **JUnit / NUnit / xUnit** – testes unitários em diferentes linguagens  
- **Postman / Newman** – testes automatizados de APIs  
- **JMeter** – testes de performance  

---

### 📚 Materiais de referência

- [O equilíbrio perfeito: automação e testes manuais na vida de uma QA - DIO](https://www.dio.me/articles/o-equilibrio-perfeito-automacao-e-testes-manuais-na-vida-de-uma-qa-51ac6d72a0a3)  
- [Teste manual vs teste automatizado - Zup Blog](https://zup.com.br/blog/teste-manual-vs-teste-automatizado/)  
- [Vídeo: Testes Manuais vs Automatizados - YouTube](https://www.youtube.com/watch?v=FClweJfSzGY)  
- [Tipos de Testes de Software - Atlassian](https://www.atlassian.com/br/continuous-delivery/software-testing/types-of-software-testing)  
- **ISTQB Foundation Level (CTFL)** - referência conceitual para abordagens de teste e estratégia de automação
