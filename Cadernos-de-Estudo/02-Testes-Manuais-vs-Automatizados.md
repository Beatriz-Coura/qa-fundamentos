## 📖 Caderno 02 – Testes Manuais vs Automatizados

### O que são Testes Manuais

Os **testes manuais** são aqueles em que o QA **executa os cenários de teste diretamente**, sem o auxílio de scripts ou ferramentas de automação.

* Envolvem seguir passo a passo os **casos de teste** previamente escritos.
* Dependem da observação e análise do testador.
* Muito úteis para verificar **experiência do usuário (UX)**, usabilidade e cenários exploratórios.

📌 Exemplos:

* Acessar a tela de login e tentar entrar com credenciais corretas e incorretas.
* Testar se o botão “Cadastrar” leva para a tela correta.
* Explorar o sistema como um usuário real faria, buscando falhas inesperadas.

✅ **Vantagens**

* Mais flexíveis (permitem exploração criativa).
* Não exigem programação.
* São mais baratos em curto prazo.

❌ **Desvantagens**

* Mais lentos e sujeitos a erros humanos.
* Difíceis de repetir em grande escala.

---

### O que são Testes Automatizados

Os **testes automatizados** são executados por meio de **scripts, códigos ou ferramentas** que reproduzem os cenários de teste de forma automática.

* Ideais para testes repetitivos e de regressão.
* Garantem maior velocidade, padronização e escalabilidade.

📌 Exemplos:

* Usar Selenium para validar automaticamente o login em diferentes navegadores.
* Testes de API com Postman automatizados em uma pipeline CI/CD.
* Testes de performance com JMeter.

✅ **Vantagens**

* Repetitivos, rápidos e consistentes.
* Executam em larga escala (ex.: milhares de cenários em minutos).
* Podem ser integrados em pipelines de entrega contínua (CI/CD).

❌ **Desvantagens**

* Alto custo inicial (tempo para criar scripts e configurar).
* Requerem conhecimentos técnicos (programação, frameworks, integração).
* Demandam manutenção constante conforme o sistema muda.

---

### Quando usar Manual e quando usar Automatizado?

**Testes Manuais são indicados quando:**

* O sistema ainda está em fase inicial (muito instável).
* É necessário validar **usabilidade e experiência do usuário**.
* O cenário é **exploratório**, sem roteiro fixo.

**Testes Automatizados são indicados quando:**

* O sistema já está estável.
* Há **grande volume de testes repetitivos** (ex.: regressão).
* Existe a necessidade de **velocidade e escala** (pipeline de CI/CD).

O segredo está no **equilíbrio**:

* Testes manuais = ótimos para encontrar falhas criativas.
* Testes automatizados = ótimos para garantir repetibilidade e velocidade.

**Conclusão**: manual é mais detalhado e adaptável, mas lento. Automação é rápida e eficiente, mas precisa de investimento e planejamento.

---

### Ferramentas mais comuns

#### **Para Testes Manuais**

* Jira / Azure DevOps → gestão de casos e bugs.
* TestRail → documentação de testes.
* Trello → gestão mais simples de atividades.

#### **Para Testes Automatizados**

* **Selenium** → automação web.
* **Cypress** → automação frontend moderna.
* **JUnit / NUnit / xUnit** → testes unitários em diferentes linguagens.
* **Postman / Newman** → testes de APIs.
* **JMeter** → testes de performance.

---

## 📚 Materiais de referência  

- [O equilíbrio perfeito: automação e testes manuais na vida de uma QA – DIO](https://www.dio.me/articles/o-equilibrio-perfeito-automacao-e-testes-manuais-na-vida-de-uma-qa-51ac6d72a0a3)  
- [Teste manual vs teste automatizado – Zup Blog](https://zup.com.br/blog/teste-manual-vs-teste-automatizado/)  
- [Vídeo: Testes Manuais vs Automatizados (YouTube)](https://www.youtube.com/watch?v=FClweJfSzGY)  
- [Tipos de Testes de Software – Atlassian](https://www.atlassian.com/br/continuous-delivery/software-testing/types-of-software-testing)  


