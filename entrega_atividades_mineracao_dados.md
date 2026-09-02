# 📚 Entrega das Atividades — Projeto de Mineração de Dados

**Disciplina:** ISW-039 — Mineração de Dados  
**Curso:** Desenvolvimento de Software Multiplataforma (DSM)

---

## 🎯 Sobre as entregas

O projeto da disciplina será desenvolvido de forma progressiva ao longo do semestre.

A nota da disciplina será **contemplada no desenvolvimento do projeto**, sendo construída a partir das entregas de cada etapa.

Cada atividade representa uma evolução do projeto, desde a definição do problema até a entrega final.

```text
AT1
Definição do Projeto
      ↓
AT2
Coleta, Limpeza e ETL
      ↓
AT3
Análise Exploratória e Visualização
      ↓
AT4
Mineração de Dados e Validação
      ↓
AT5
Entrega Final
```

> **Importante:** as atividades não são projetos independentes. Cada entrega deve aproveitar e evoluir o trabalho realizado na etapa anterior.

---

# 📅 Cronograma de Entregas

| Atividade | Etapa | Conteúdos relacionados | Data de entrega |
|---|---|---|---:|
| **AT1** | Definição do Projeto | Aulas 1 e 2 | **03/09/2026** |
| **AT2** | Coleta, Limpeza e ETL | Aulas 3 a 5 | **17/09/2026** |
| **AT3** | Análise Exploratória e Visualização | Aulas 6 a 10 | **15/10/2026** |
| **AT4** | Mineração de Dados e Validação | Aulas 11 a 15 | **12/11/2026** |
| **AT5** | Entrega Final do Projeto | Consolidação do projeto | **04/12/2026** |

---

# 1️⃣ AT1 — Definição do Projeto

📅 **Entrega: 02/09/2026**

### Objetivo

Definir o problema que será investigado utilizando técnicas de Mineração de Dados.

### A entrega deverá apresentar

- Tema do projeto;
- Contextualização;
- Problema de negócio;
- Entendimento do negócio;
- Pergunta que será investigada;
- Objetivo geral;
- Objetivos específicos;
- Fonte de dados pretendida;
- Justificativa da escolha do problema;
- Integrantes do grupo.

### Pergunta central

> **Qual problema queremos investigar utilizando dados?**

### Entrega no GitHub

```text
README.md
```

O README deverá apresentar a proposta inicial do projeto.

---

# 2️⃣ AT2 — Coleta, Limpeza e ETL

📅 **Entrega: 16/09/2026**

### Objetivo

Construir uma primeira versão da base de dados que será utilizada no projeto.

### A entrega deverá apresentar

- Fonte dos dados;
- Processo de coleta;
- Dados brutos;
- Identificação das variáveis;
- Estrutura da base;
- Tratamento de valores ausentes;
- Tratamento de duplicidades;
- Correção de tipos;
- Tratamento de inconsistências;
- Transformações realizadas;
- Processo ETL;
- Base de dados preparada para análise.

### Tecnologias

Utilizar Python e Pandas, podendo utilizar outras ferramentas conforme a fonte dos dados.

### Entrega no GitHub

Sugestão de organização:

```text
projeto/
│
├── README.md
├── dados/
│   ├── dados_brutos/
│   └── dados_tratados/
│
└── notebooks/
    └── etl.ipynb
```

---

# 3️⃣ AT3 — Análise Exploratória e Visualização

📅 **Entrega: 14/10/2026**

### Objetivo

Investigar os dados e identificar padrões, tendências, relações e características relevantes para o problema.

### A entrega deverá apresentar

- Análise da estrutura da base;
- Estatística descritiva;
- Média;
- Mediana;
- Medidas de dispersão;
- Distribuição das variáveis;
- Análise de variáveis categóricas;
- Identificação de possíveis outliers;
- Análise de correlação, quando aplicável;
- Gráficos adequados ao problema;
- Interpretação das visualizações;
- Principais descobertas realizadas até esta etapa.

### Pergunta central

> **O que os dados estão revelando sobre o problema?**

### Entrega no GitHub

```text
notebooks/
    └── eda.ipynb

resultados/
    └── graficos/
```

---

# 4️⃣ AT4 — Mineração de Dados e Validação

📅 **Entrega: 11/11/2026**

### Objetivo

Aplicar uma ou mais técnicas de Mineração de Dados adequadas ao problema e avaliar os resultados obtidos.

### A entrega deverá apresentar

- Preparação dos dados para modelagem;
- Seleção de atributos;
- Engenharia de atributos, quando aplicável;
- Definição da variável alvo, quando aplicável;
- Escolha da técnica de Mineração de Dados;
- Justificativa da técnica escolhida;
- Treinamento do modelo;
- Teste do modelo;
- Métricas de avaliação;
- Validação;
- Comparação entre modelos, quando aplicável;
- Interpretação dos resultados;
- Limitações encontradas.

### Técnicas possíveis

Dependendo do problema:

- Classificação;
- Regressão;
- Clusterização;
- Regras de Associação;
- Redes Neurais;
- Outras técnicas estudadas na disciplina.

### Pergunta central

> **A técnica escolhida consegue ajudar a responder ao problema definido no projeto?**

### Entrega no GitHub

```text
notebooks/
    └── modelagem.ipynb

src/
    └── ...

resultados/
    └── ...
```

---

# 5️⃣ AT5 — Entrega Final do Projeto

📅 **Entrega: 03/12/2026**

### Objetivo

Consolidar todas as etapas desenvolvidas durante o semestre em um projeto completo de Mineração de Dados.

### A entrega final deverá conter

- Problema;
- Objetivos;
- Fonte dos dados;
- Coleta;
- ETL;
- Limpeza;
- Análise exploratória;
- Visualizações;
- Pré-processamento;
- Engenharia de atributos, quando aplicável;
- Técnica de Mineração de Dados;
- Modelagem;
- Avaliação;
- Validação;
- Resultados;
- Interpretação;
- Conclusão;
- Limitações;
- Possíveis trabalhos futuros.

### Repositório GitHub

O projeto deverá estar organizado e documentado.

Sugestão:

```text
projeto-mineracao-dados/
│
├── README.md
│
├── dados/
│   ├── dados_brutos/
│   └── dados_tratados/
│
├── notebooks/
│   ├── coleta.ipynb
│   ├── etl.ipynb
│   ├── eda.ipynb
│   └── modelagem.ipynb
│
├── src/
│   └── ...
│
├── resultados/
│   ├── graficos/
│   └── modelos/
│
├── dashboard/
│   └── ...
│
└── requirements.txt
```

A estrutura poderá ser adaptada de acordo com as características de cada projeto.

---

# 📊 Evolução esperada do projeto

Ao final das cinco atividades, o projeto deverá apresentar a seguinte evolução:

```text
AT1
Problema
  ↓
AT2
Dados
  ↓
AT3
Conhecimento
  ↓
AT4
Modelo
  ↓
AT5
Solução
```

Ou, considerando o processo completo:

```text
ENTENDIMENTO DO NEGÓCIO
        ↓
COLETA DOS DADOS
        ↓
ETL
        ↓
LIMPEZA
        ↓
EDA
        ↓
VISUALIZAÇÃO
        ↓
PRÉ-PROCESSAMENTO
        ↓
MINERAÇÃO
        ↓
MODELAGEM
        ↓
VALIDAÇÃO
        ↓
INTERPRETAÇÃO
        ↓
CONCLUSÃO
```

---

# 🐙 GitHub — Controle da evolução

O GitHub será utilizado para registrar a evolução do projeto.

Recomenda-se realizar commits durante o desenvolvimento, evitando deixar todo o trabalho para o dia da entrega.

Exemplo:

```text
feat: adiciona base inicial
feat: implementa processo ETL
feat: adiciona análise exploratória
feat: adiciona visualizações
feat: implementa modelo de classificação
feat: adiciona validação
docs: atualiza README
```

> O histórico do repositório poderá ser utilizado para acompanhar a evolução do projeto.

---

# 💻 Ambientes de desenvolvimento

Durante a disciplina serão utilizados:

### Google Colab

Utilizado principalmente para:

- aulas práticas;
- notebooks;
- experimentação;
- análise de dados;
- testes de algoritmos.

### PyCharm

Utilizado principalmente para:

- organização do projeto;
- desenvolvimento Python;
- criação de scripts;
- estruturação da aplicação;
- gerenciamento das bibliotecas.

### GitHub

Utilizado para:

- versionamento;
- documentação;
- armazenamento do código;
- acompanhamento da evolução;
- construção do portfólio.

---

# ⚠️ Regras importantes

### 1. Os dados devem possuir fonte identificada

Informe de onde os dados foram obtidos.

### 2. Não coloque credenciais no GitHub

Nunca publique:

- senhas;
- tokens;
- chaves de API;
- credenciais de banco;
- informações pessoais sensíveis.

### 3. Documente as decisões

Explique **o que foi feito e por quê**.

### 4. Não basta apresentar código

O projeto deverá apresentar:

```text
Código
+
Análise
+
Resultados
+
Interpretação
```

### 5. A técnica deve estar relacionada ao problema

Não escolha um algoritmo simplesmente porque ele foi apresentado em aula.

A escolha deverá ser justificada.

---

# 🎯 Critério geral para todas as entregas

Em cada etapa, procure responder:

> **O que foi feito?**

> **Por que foi feito?**

> **Como foi feito?**

> **O que os dados/resultados mostram?**

Essa lógica deverá acompanhar o projeto desde a primeira até a última entrega.

---

# 🚀 Entrega Final

A última entrega deverá representar a evolução completa do trabalho desenvolvido durante o semestre.

O projeto será apresentado em formato de **Pitch Final**, demonstrando:

1. Problema;
2. Dados;
3. Método;
4. Resultados;
5. Conclusão.

> **O projeto começa com uma pergunta e termina com uma resposta baseada em dados.**
