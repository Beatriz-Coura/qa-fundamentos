## 📖 Caderno 03 - Bugs e Ciclo de Vida do Defeito

### Introdução

Encontrar e reportar bugs é uma das atividades mais conhecidas do QA.  
No entanto, no dia a dia profissional, o mais importante não é apenas identificar um erro, mas **comunicar o problema de forma clara e rastreável**, ajudando o time a resolvê-lo.

Segundo o **ISTQB Foundation Level (CTFL)**, um defeito faz parte do processo de desenvolvimento e deve ser tratado como algo natural, não como uma falha individual.

---

### 🐞 O que é um Bug?

Um **bug** (ou defeito) é qualquer comportamento do sistema que **não atende ao esperado**, seja por erro de implementação, requisito mal definido ou falha de integração.

De forma prática, um bug acontece quando:

- o sistema faz algo que **não deveria fazer**
- o sistema **não faz** algo que deveria fazer

#### Exemplos comuns

- Botão que não responde ao clique  
- Campo que aceita dados inválidos  
- Sistema que apresenta informações incorretas  
- Aplicação que fecha inesperadamente  

No contexto do CTFL, é importante diferenciar:

- **Erro (Error)** → ação humana incorreta  
- **Defeito (Defect)** → problema no código ou artefato  
- **Falha (Failure)** → defeito percebido em execução  

---

### Ciclo de Vida do Bug (Bug Life Cycle)

O **ciclo de vida do bug** representa as etapas pelas quais um defeito passa desde sua identificação até sua resolução.

Embora as ferramentas e fluxos variem entre empresas, o conceito geral é o seguinte:

| Status | Descrição |
|------|-----------|
| Novo (New) | Bug identificado e registrado pelo QA |
| Atribuído (Assigned) | Bug atribuído a um desenvolvedor |
| Em andamento (In Progress) | Defeito em análise ou correção |
| Resolvido (Fixed/Resolved) | Correção aplicada |
| Reteste (Retesting) | QA valida a correção |
| Fechado (Closed) | Bug confirmado como corrigido |
| Reaberto (Reopened) | Bug ainda persiste após correção |

Outros status comuns:
- **Duplicado**
- **Não reproduzido**
- **Não é bug**

---

### Como relatar um Bug

Um bom **relatório de bug** deve permitir que qualquer pessoa do time consiga **reproduzir o problema sem dúvidas**.

#### Estrutura comum de um bug report

- **Título**: descrição curta e objetiva do problema  
- **Ambiente**: onde o bug ocorreu (dev, homologação, produção)  
- **Passos para reprodução**: passo a passo do erro  
- **Resultado esperado**: o que deveria acontecer  
- **Resultado obtido**: o que aconteceu de fato  
- **Severidade e prioridade**: impacto e urgência  
- **Evidências**: prints, vídeos ou logs  

💡 Quanto mais claro o bug report, **mais rápido o time consegue corrigir**.

---

### Ferramentas de Gestão de Bugs

Ferramentas de gestão ajudam a organizar, priorizar e acompanhar os defeitos encontrados.

Algumas das mais utilizadas no mercado:

- **Jira** - amplamente usado em times ágeis  
- **Azure DevOps** - integrado a pipelines e boards  
- **Trello** - opção simples para times pequenos  
- **Bugzilla / Mantis** - alternativas open source  

---

### 📚 Materiais de referência

- [O que é bug? - KingHost](https://king.host/blog/tecnologia/o-que-e-bug/)  
- [Relatório de Bug: guia detalhado e boas práticas - DIO](https://www.dio.me/articles/relatorio-de-bug-guia-detalhado-e-boas-praticas)  
- [Como escrever um bug report - Medium (Ronilson Ribeiro)](https://medium.com/@ronilsonribeiro/como-escrever-um-bug-report-4041c231fdab)  
- **ISTQB Foundation Level (CTFL)** - referência conceitual para defeitos, falhas e ciclo de vida do bug
