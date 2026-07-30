# 🚀 PROJETO INTEGRADOR

# Disciplina: Mineração de Dados (ISW-039)

> **Curso:** Desenvolvimento de Software Multiplataforma (DSM)
> **Instituição:** Fatec Indaiatuba – Centro Paula Souza
> **Professor:** Prof. Dr. Wellington Roque

---

# Sobre o Projeto

O Projeto Integrador representa a principal atividade da disciplina de **Mineração de Dados**.

Durante todo o semestre cada grupo desenvolverá uma solução completa para um problema real utilizando técnicas de Ciência de Dados, Inteligência Artificial e Mineração de Dados.

O projeto será construído de forma incremental, acompanhando os conteúdos desenvolvidos em sala de aula.

Ao final do semestre cada equipe terá desenvolvido um projeto semelhante aos encontrados no mercado de trabalho.

---

# Objetivo

Aplicar, de forma integrada, todos os conhecimentos estudados durante a disciplina para transformar dados em conhecimento útil para apoiar a tomada de decisão.

---

# Organização dos Grupos

Cada projeto deverá ser desenvolvido por grupos de:

* 2 ou 3 estudantes

Todos os integrantes deverão participar das atividades.

O histórico de commits será utilizado para acompanhar a participação individual.

---

# Estrutura Geral do Projeto

Todo projeto deverá seguir o fluxo abaixo.

```text
Definição do Problema
        │
        ▼
Coleta dos Dados
        │
        ▼
ETL
        │
        ▼
Preparação dos Dados
        │
        ▼
Análise Exploratória (EDA)
        │
        ▼
Mineração de Dados
        │
        ▼
Avaliação dos Resultados
        │
        ▼
Dashboard
        │
        ▼
GitHub
        │
        ▼
Pitch Final
```

---

# Escolha do Tema

O tema deverá abordar um problema real.

Exemplos:

* Educação
* Saúde
* Mobilidade Urbana
* Segurança Pública
* Agricultura
* Indústria
* IoT
* Finanças
* Redes Sociais
* Marketing
* Meio Ambiente
* Governo Digital

Outros temas poderão ser aprovados pelo professor.

---

# Fontes de Dados

Os dados poderão ser obtidos por meio de:

* Kaggle
* Dados.gov.br
* IBGE
* INEP
* SUS
* APIs Públicas
* Web Scraping
* Empresas
* Sensores IoT
* Bases próprias

É obrigatório informar a origem dos dados e verificar as condições de uso da base escolhida.

---

# Estrutura do Repositório

Cada grupo deverá criar um repositório no GitHub utilizando a estrutura abaixo.

```text
projeto-mineracao-dados/

│
├── README.md
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── external/
│
├── notebooks/
│
├── src/
│
├── dashboard/
│
├── models/
│
├── reports/
│
├── images/
│
├── requirements.txt
│
└── LICENSE
```

---

# Desenvolvimento do Projeto

## Sprint 1 — Definição do Problema

### Entregáveis

* Tema
* Problema
* Objetivos
* Justificativa
* Perguntas que serão respondidas
* Fonte dos dados

### Exemplo

**Tema**

Educação

**Problema**

Quais fatores influenciam a evasão escolar?

---

## Sprint 2 — Coleta dos Dados

Nesta etapa os grupos deverão:

* Obter os dados
* Organizar os arquivos
* Documentar a origem
* Descrever os atributos
* Verificar licenças de uso

### Entregáveis

* Dataset
* Dicionário de dados
* Documentação da coleta

---

## Sprint 3 — ETL

Nesta etapa deverão ser desenvolvidos os processos de:

* Extração
* Transformação
* Limpeza
* Organização

### Técnicas esperadas

* Valores ausentes
* Dados duplicados
* Conversão de tipos
* Padronização
* Tratamento de inconsistências

### Entregáveis

Notebook documentado.

---

## Sprint 4 — Preparação dos Dados

Aplicação de:

* Normalização
* Padronização
* Encoding
* Balanceamento
* Engenharia de atributos

### Entregáveis

Base preparada para mineração.

---

## Sprint 5 — Análise Exploratória

Produzir:

* Estatísticas descritivas
* Correlações
* Histogramas
* Boxplots
* Heatmaps
* Scatterplots

Responder perguntas importantes utilizando os dados.

---

## Sprint 6 — Mineração de Dados

Selecionar as técnicas mais adequadas ao problema.

Exemplos:

### Classificação

* Regressão Logística
* Árvore de Decisão
* Random Forest
* KNN

### Clusterização

* K-Means
* DBSCAN

### Associação

* Apriori

### Redes Neurais

* MLP

Os grupos deverão justificar a escolha dos algoritmos utilizados.

---

## Sprint 7 — Dashboard

Construção de um painel contendo:

* Indicadores
* Gráficos
* Métricas
* Filtros
* Conclusões

Ferramentas sugeridas:

* Streamlit
* Dash
* Power BI

---

## Sprint 8 — Organização do Projeto

Revisão completa do GitHub.

Checklist:

* README
* Código organizado
* Notebook comentado
* Dashboard funcionando
* Dataset documentado

---

## Sprint 9 — Pitch Final

Apresentação da solução desenvolvida.

Tempo:

* 10 minutos de apresentação
* 5 minutos para perguntas

---

# Critérios de Avaliação

| Sprint   | Avaliação                                    | Peso |
| -------- | -------------------------------------------- | ---: |
| Sprint 1 | Planejamento do projeto                      |  10% |
| Sprint 2 | Coleta e organização dos dados               |  15% |
| Sprint 3 | ETL e preparação dos dados                   |  20% |
| Sprint 4 | Análise Exploratória                         |  15% |
| Sprint 5 | Aplicação das técnicas de Mineração de Dados |  20% |
| Sprint 6 | Dashboard e documentação                     |  10% |
| Sprint 7 | Pitch Final                                  |  10% |

---

# Critérios Técnicos

Serão avaliados:

* Organização do projeto
* Clareza do problema
* Qualidade dos dados
* Aplicação correta das técnicas
* Qualidade do código
* Documentação
* Visualização dos resultados
* GitHub
* Trabalho em equipe
* Comunicação

---

# Boas Práticas

Durante o desenvolvimento recomenda-se:

* Realizar commits frequentes.
* Utilizar branches quando necessário.
* Escrever mensagens de commit significativas.
* Documentar todas as decisões importantes.
* Comentar trechos complexos do código.
* Manter notebooks organizados.
* Utilizar nomes claros para arquivos e variáveis.

---

# Requisitos para Aprovação

Ao final do semestre cada grupo deverá entregar:

* Repositório GitHub completo.
* Projeto funcional.
* Notebooks organizados.
* Código documentado.
* Dashboard.
* Relatório Técnico.
* README do projeto.
* Apresentação (Pitch).

Projetos incompletos ou sem documentação adequada poderão sofrer redução na nota, conforme os critérios de avaliação.

---

# Dicas para um Bom Projeto

* Escolha um problema que desperte interesse do grupo.
* Priorize bases de dados confiáveis.
* Documente todas as etapas do desenvolvimento.
* Evite copiar projetos prontos da internet.
* Justifique todas as decisões técnicas.
* Utilize gráficos para comunicar resultados.
* Pense no projeto como parte do seu portfólio profissional.

---

# Mensagem Final

O objetivo deste projeto não é apenas aplicar algoritmos de Mineração de Dados, mas desenvolver uma solução completa para um problema real, seguindo um processo semelhante ao adotado por equipes de Ciência de Dados em empresas.

Ao final da disciplina, espera-se que cada grupo tenha construído um projeto que demonstre competências em coleta, preparação, análise, modelagem, visualização e comunicação de dados, servindo como evidência prática de sua formação e podendo integrar seu Portfólio Digital e currículo profissional.

Desejamos um excelente semestre e um ótimo desenvolvimento do projeto. 🚀
