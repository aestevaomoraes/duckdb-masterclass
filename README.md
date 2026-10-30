# 🎓 DuckDB Masterclass — Do Básico ao Especialista

### Engenharia Analítica | SQL Avançado | Data Engineering | Operations Analytics

Formação prática e progressiva em **DuckDB**, utilizando **Jupyter Notebook** como ambiente principal de aprendizagem, experimentação e desenvolvimento de soluções analíticas.

Este repositório reúne materiais didáticos, exemplos SQL, códigos Python, laboratórios e desafios aplicados à Engenharia de Dados e à Análise de Dados.

**Autor:** Antonio Estevão de Moraes Neto  
**Formato:** Jupyter Notebook (`.ipynb`)  
**Idioma:** Português (Brasil)  
**Status:** Formação em desenvolvimento e validação contínua.

---

## 🎯 Objetivo da Masterclass

Desenvolver competências técnicas para utilizar o DuckDB em projetos de análise e engenharia de dados, desde os fundamentos da arquitetura OLAP até consultas avançadas, integração com ferramentas de dados e otimização de desempenho.

A proposta combina:

- Fundamentação conceitual e técnica.
- SQL analítico aplicado a problemas de negócio.
- Integração entre DuckDB, Python, Pandas e Apache Arrow.
- Laboratórios executáveis no Jupyter Notebook.
- Exercícios de investigação e validação.
- Desafios de Operations Analytics.

O objetivo é desenvolver autonomia para **projetar, implementar, analisar e otimizar soluções com DuckDB**.

## 🧠 Metodologia de aprendizagem

Cada capítulo busca seguir uma abordagem progressiva:

**Conceito → Teoria → Laboratório guiado → Experimentação → Desafio profissional → Avaliação.**

Os notebooks são acompanhados de atividades de mentoria e revisão técnica. A proposta incentiva o aluno a interpretar resultados e compreender decisões de engenharia, em vez de apenas reproduzir comandos.

## 📚 Estrutura curricular

| Cap. | Tema |
|---|---|
| 00 | [Manual do Mochileiro — Jupyter Notebook](00_Manual_do_Mochileiro_Jupyter_Notebook.ipynb) |
| 01 | [Arquitetura OLAP In-Process e Benchmark TPC-H](01_Arquitetura_OLAP_In-Process_e_Benchmark_TPC-H.ipynb) |
| 02 | [Transações ACID, Concorrência, MVCC e WAL](02_Transacoes_ACID_Concorrencia_MVCC_e_o_WAL.ipynb) |
| 03 | [Tipagem Avançada: LIST, STRUCT, MAP e JSON](03_Tipagem_Avancada_LIST_STRUCT_MAP_e_JSON_Nativo.ipynb) |
| 04 | [Ingestão de Dados e Friendly SQL](04_Ingestao_Zero_Copy_e_o_Dialeto_Friendly_SQL2710.ipynb) |
| 05 | [Window Functions, QUALIFY e PIVOT Dinâmico](05_Window_Functions_QUALIFY_e_PIVOT_Dinamico.ipynb) |
| 06 | [Junções Temporais com ASOF JOIN e Séries Temporais](06_Juncoes_Temporais_com_ASOF_JOIN_e_Series_Temporais.ipynb) |
| 07 | [Metaprogramação SQL: Macros e Table UDFs](07_Metaprogramacao_em_SQL_Macros_e_Table_UDFs.ipynb) |
| 08 | [Federação de Dados: PostgreSQL, MySQL e SQLite](08_Federacao_de_Dados_PostgreSQL_MySQL_e_SQLite.ipynb) |
| 09 | [Extensões de Nuvem e Secrets Manager](09_Extensoes_de_Nuvem_e_Secrets_Manager_Corporativo.ipynb) |
| 10 | [Lakehouses: Apache Iceberg e Delta Lake](10_Lakehouses_Corporativos_Apache_Iceberg_e_Delta_Lake.ipynb) |
| 11 | [Analytics Engineering com dbt e DuckDB](11_Analytics_Engineering_com_dbt_duckdb.ipynb) |
| 12 | [Internals: Zonemaps e Índices ART](12_Internals_de_Armazenamento_Zonemaps_e_Indices_ART.ipynb) |
| 13 | [Profiling, EXPLAIN ANALYZE e Out-of-Core Execution](13_Profiling_EXPLAIN_ANALYZE_e_Out_of_Core_Execution.ipynb) |
| 14 | [DuckDB em Produção: Arrow, Wasm e MotherDuck](14_DuckDB_em_Producao_Arrow_Wasm_e_MotherDuck.ipynb) |

Consulte também o [índice e plano de estudos](00_Indice_e_Plano_de_Estudos.ipynb).

Os capítulos foram organizados para aumentar gradualmente a complexidade. Algumas atividades avançadas podem exigir extensões ou serviços externos.

## 💻 Tecnologias utilizadas

- **DuckDB:** mecanismo analítico SQL.
- **Python:** automação, integração e execução dos laboratórios.
- **Jupyter Notebook/JupyterLab:** ambiente didático.
- **Pandas:** manipulação de DataFrames.
- **Apache Arrow / PyArrow:** interoperabilidade e processamento colunar.
- **Git e GitHub:** controle de versões e documentação.

## 🚀 Como executar os laboratórios

**1. Clone o repositório:**

```bash
git clone https://github.com/aestevaomoraes/duckdb-masterclass.git
cd duckdb-masterclass
```

**2. Crie e ative um ambiente virtual (Windows, Prompt de Comando ou Anaconda Prompt):**

```bat
python -m venv .venv
.venv\Scripts\activate
```

**3. Instale as dependências:**

```bash
python -m pip install -r requirements.txt
```

**4. Registre um kernel para a formação:**

```bash
python -m ipykernel install --user --name duckdb-masterclass --display-name "Python (DuckDB Masterclass)"
```

**5. Inicie o JupyterLab:**

```bash
jupyter lab
```

Abra o [Manual do Mochileiro — Jupyter Notebook](00_Manual_do_Mochileiro_Jupyter_Notebook.ipynb) e siga as orientações para selecionar o kernel e executar as células.

> **Reprodutibilidade:** o `requirements.txt` registra as versões instaladas no ambiente de preparação. Dependências e extensões específicas de alguns capítulos podem exigir configurações adicionais. A instalação exata também depende da plataforma e da versão do Python.

## 🧪 Aplicações em Operations Analytics

Os laboratórios exploram situações como:

- Análise de indicadores operacionais.
- Classificação e comparação de desempenho.
- Tratamento de arquivos CSV, JSON e Parquet.
- Séries temporais e vigência de tarifas.
- Qualidade, consistência e transformação de dados.
- Otimização de consultas SQL.
- Preparação de dados para análises e relatórios.

Os exemplos são didáticos e não representam necessariamente dados de operações reais.

## ✅ Estado de validação

A Masterclass encontra-se em processo de desenvolvimento e revisão técnica.

A primeira reconstrução passou por verificações estruturais e de sintaxe Python, mas isso **não equivale à validação integral das consultas DuckDB, integrações e extensões**.

Os laboratórios serão avaliados progressivamente quanto à execução, reprodutibilidade, precisão conceitual e qualidade didática.

Consulte o [relatório de validação](RELATORIO_VALIDACAO.md) para conhecer as verificações documentadas.

## 📖 Referências oficiais

- [DuckDB — Documentação](https://duckdb.org/docs/stable/)
- [DuckDB — Python API](https://duckdb.org/docs/stable/clients/python/overview)
- [DuckDB — SQL Introduction](https://duckdb.org/docs/stable/sql/introduction)
- [Jupyter — Documentação](https://docs.jupyter.org/)
- [Apache Arrow](https://arrow.apache.org/docs/)
- [Pandas — Documentação](https://pandas.pydata.org/docs/)

## ✍️ Autoria e propósito educacional

Projeto educacional desenvolvido por **Antonio Estevão de Moraes Neto**, com foco no aprofundamento de competências em Engenharia Analítica, SQL e tecnologias modernas de dados.

Os materiais são continuamente aprimorados por meio de estudos, exercícios, experimentação e mentoria com apoio de inteligência artificial.

O repositório também funciona como material complementar para publicações técnicas e artigos educacionais.

---

**DuckDB Masterclass — Aprender os conceitos, experimentar a tecnologia e desenvolver autonomia em Engenharia de Dados.**
