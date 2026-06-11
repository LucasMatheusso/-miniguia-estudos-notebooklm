#  Miniguia de Estudos: Análise de Dados e Business Intelligence

> Projeto desenvolvido como parte do desafio prático da DIO — uso do NotebookLM como ferramenta de aprendizagem ativa em Análise de Dados e BI.

---

##  Contexto e Objetivos

### Tema Escolhido
**Análise de Dados e Business Intelligence (BI)** — com foco nos fundamentos práticos que permitem transformar dados brutos em decisões de negócio.

### Objetivos de Estudo
- Compreender o fluxo completo de análise de dados: coleta → transformação → visualização → decisão
- Dominar os conceitos centrais de BI: KPIs, dashboards, métricas e relatórios
- Entender as diferenças entre análise descritiva, diagnóstica, preditiva e prescritiva
- Conhecer as principais ferramentas do mercado (Power BI, SQL, Python/Pandas)
- Construir um vocabulário técnico sólido para atuar na área

---

##  Curadoria de Fontes

As fontes abaixo foram selecionadas por serem abertas, gratuitas e reconhecidas na área. Todas foram inseridas no NotebookLM para análise.

| # | Fonte | Tipo | Link |
|---|-------|------|------|
| 1 | **Storytelling with Data** – capítulos selecionados (Cole Nussbaumer) | PDF/Web | [storytellingwithdata.com](https://www.storytellingwithdata.com/blog) |
| 2 | **Google Data Analytics Certificate** – materiais públicos do Coursera | PDF | [coursera.org/professional-certificates/google-data-analytics](https://www.coursera.org/professional-certificates/google-data-analytics) |
| 3 | **Business Intelligence Guidebook** – trechos abertos (Rick Sherman) | PDF | [tdwi.org](https://tdwi.org/research/list/tdwi-best-practices-reports.aspx) |
| 4 | **Documentação oficial do Power BI** – Microsoft Learn | Web/PDF | [learn.microsoft.com/pt-br/power-bi](https://learn.microsoft.com/pt-br/power-bi/) |
| 5 | **SQL para Análise de Dados** – Mode Analytics (guia gratuito) | Web | [mode.com/sql-tutorial](https://mode.com/sql-tutorial/) |

>  **Como usar:** Faça o download ou copie os conteúdos dessas fontes e insira no NotebookLM em [notebooklm.google.com](https://notebooklm.google.com)

---

##  Engenharia de Prompts e "Cicatrizes"

### Prompts Estratégicos Utilizados

####  Bloco 1 — Compreensão Inicial

**Prompt 1:**
```
Explique o conceito de Business Intelligence para alguém com background em exatas, mas sem experiência prévia em dados corporativos.
```
 *Resultado:* Boa resposta contextualizada. A IA conectou BI com tomada de decisão baseada em dados, citando os materiais carregados.

---

**Prompt 2:**
```
Qual é a diferença entre dado, informação, conhecimento e sabedoria no contexto da pirâmide DIKW aplicada a BI?
```
 *Resultado:* Explicação clara com exemplos práticos de cada nível.

---

#### 🔹 Bloco 2 — Aprofundamento

**Prompt 3:**
```
Com base nas fontes carregadas, quais são os principais tipos de análise de dados? Dê um exemplo prático de cada um para o contexto de uma empresa de varejo.
```
 *Resultado:* Excelente. O NotebookLM referenciou trechos específicos dos materiais e aplicou ao varejo conforme solicitado.

---

**Prompt 4:**
```
Liste os 10 KPIs mais utilizados em dashboards de BI para o setor de varejo, explicando o que cada um mede e por que é importante.
```
*Dificuldade encontrada:* A resposta inicial foi genérica demais. Foi necessário refinar o prompt.

**Prompt refinado:**
```
Considerando especificamente as fontes que careguei, quais métricas de desempenho (KPIs) para varejo são mais citadas? Organize em uma tabela com: nome do KPI, fórmula de cálculo e objetivo estratégico.
```
 *Resultado após refinamento:* Resposta muito mais estruturada e embasada nas fontes.

---

####  Bloco 3 — Síntese e Revisão

**Prompt 5:**
```
Crie um resumo executivo de no máximo 5 parágrafos sobre os principais conceitos de Análise de Dados e BI abordados nas fontes que carreguei.
```
 *Resultado:* Ótimo resumo com referências cruzadas entre os materiais.

---

**Prompt 6:**
```
Elabore 10 perguntas de revisão (estilo prova) sobre os conceitos de BI e Análise de Dados presentes nas fontes, com gabarito comentado.
```
 *Resultado:* Perguntas bem formuladas, úteis para fixação do conteúdo.

---

### 🩹 Dificuldades Encontradas (Troubleshooting)

| Problema | Causa | Solução |
|---------|-------|---------|
| Respostas vagas e genéricas | Prompt amplo demais | Adicionar contexto específico: setor, formato desejado, número de itens |
| IA ignorou uma das fontes | Fonte em formato pouco legível | Converter PDF para texto antes de inserir no NotebookLM |
| Resposta sem referências | Faltou instrucionar sobre citações | Adicionar "cite os trechos das fontes que embasaram essa resposta" |
| Repetição de conteúdo | Fontes com sobreposição temática | Selecionar fontes mais complementares entre si |

---

##  Miniguia de Estudo (Entrega Final)

###  Resumos Estruturados

#### 1. O que é Análise de Dados?
Análise de dados é o processo de inspecionar, limpar, transformar e modelar dados com o objetivo de descobrir informações úteis, tirar conclusões e apoiar a tomada de decisão. O processo segue um ciclo: **coleta → limpeza → análise → visualização → ação**.

#### 2. O que é Business Intelligence (BI)?
BI é um conjunto de tecnologias, processos e práticas que transformam dados brutos em informações estratégicas para o negócio. Um sistema de BI típico inclui: **data warehouse**, **ETL** (extração, transformação e carga), **dashboards** e **relatórios**.

#### 3. Os 4 Tipos de Análise
| Tipo | Pergunta que responde | Exemplo |
|------|-----------------------|---------|
| **Descritiva** | O que aconteceu? | Vendas do mês foram R$ 500k |
| **Diagnóstica** | Por que aconteceu? | Queda nas vendas por falta de estoque |
| **Preditiva** | O que vai acontecer? | Previsão de demanda para o próximo trimestre |
| **Prescritiva** | O que fazer? | Recomendação automática de reposição de estoque |

#### 4. Ferramentas Essenciais
- **SQL** — linguagem fundamental para consultar e manipular dados
- **Power BI / Tableau** — visualização e criação de dashboards
- **Python (Pandas, Matplotlib)** — análise e automação
- **Excel** — ferramenta acessível para análises rápidas e modelagem

#### 5. Boas Práticas em Dashboards
- Menos é mais: evite poluição visual
- Hierarquia de informação: dado mais importante em destaque
- Use as cores com intenção (vermelho = alerta, verde = positivo)
- Sempre responda "qual é a história que esse dashboard conta?"

---

###  Glossário dos Principais Conceitos

| Termo | Definição |
|-------|-----------|
| **KPI** | Key Performance Indicator — métrica usada para avaliar o sucesso de um objetivo |
| **Dashboard** | Painel visual que consolida métricas e indicadores em tempo real |
| **ETL** | Extract, Transform, Load — processo de integração de dados de diferentes fontes |
| **Data Warehouse** | Repositório centralizado de dados históricos estruturados para análise |
| **Data Lake** | Armazenamento de dados brutos em seu formato original (estruturado e não estruturado) |
| **DIKW** | Pirâmide Dado → Informação → Conhecimento → Sabedoria |
| **Granularidade** | Nível de detalhe dos dados (ex: vendas por hora vs por mês) |
| **Drill-down** | Capacidade de navegar de um nível agregado para um mais detalhado no dashboard |
| **Slice and Dice** | Filtrar e segmentar dados por diferentes dimensões |
| **Data-driven** | Cultura organizacional de tomar decisões baseadas em dados |

---

###  Prompts Reutilizáveis para Futuras Revisões

```
1. "Explique [conceito] como se eu fosse um analista de dados iniciante, com um exemplo prático do setor de [setor]."

2. "Compare [ferramenta A] e [ferramenta B] em termos de: casos de uso, curva de aprendizado e mercado de trabalho."

3. "Crie um mapa mental textual dos principais conceitos de [tema], organizados por categoria."

4. "Liste os 5 erros mais comuns que iniciantes cometem em [tema] e como evitá-los."

5. "Elabore um plano de estudo de 4 semanas para dominar [tema], com recursos gratuitos recomendados."

6. "Com base nas fontes carregadas, crie 10 flashcards no formato: Pergunta / Resposta, sobre [tema]."

7. "Quais são as tendências atuais de mercado em [tema]? Cite dados ou referências presentes nas fontes."

8. "Simule uma entrevista técnica para a vaga de [cargo], fazendo perguntas sobre [tema] e avaliando minhas respostas."
```


##  Autor

Projeto desenvolvido como entrega do desafio prático da [DIO](https://www.dio.me) — Bootcamp de Análise de Dados.

---

