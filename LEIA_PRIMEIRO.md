# DuckDB Masterclass — Pacote editorial 03–14

**Data de preparação:** 2026-11-03
**Escopo:** notebooks autocontidos para estudo autônomo; dados sintéticos.
**Status técnico:** estrutura do notebook e sintaxe Python validadas; **execução integral em DuckDB 2.0 no kernel do usuário pendente**.

## Como usar
1. Faça backup dos originais ou utilize Git antes de substituí-los. Evite apagar versões previamente aprofundadas, sobretudo os capítulos 05 e 06, sem guardar uma cópia.
2. Abra cada notebook pelo Jupyter na ordem 03→14; selecione **Python (DuckDB Masterclass)**.
3. Execute `Kernel → Restart Kernel and Run All Cells`; observe erros, dados, tabelas e saídas. Laboratórios de extensão e dbt podem exigir dependências instaladas.
4. Revise o `.gitignore` para `*.duckdb`, `*.duckdb.wal`, `*.sqlite`, `*.parquet`, `.venv/`, `.ipynb_checkpoints/` e diretórios de dados temporários. Tenha cuidado: somente ignore arquivos gerados, não datasets públicos deliberadamente versionados.
5. Somente após execução e revisão de privacidade, salve, faça commit e publique.

## Escopo por capítulo
- **03** LIST, STRUCT, MAP e JSON (piloto aprovado).
- **04** Parquet e Friendly SQL (piloto aprovado).
- **05** Window Functions, QUALIFY, PIVOT/UNPIVOT, ROWS/RANGE.
- **06** ASOF JOIN, tarifas por vigência, auditoria e séries determinísticas.
- **07** Macros SQL e UDFs Python.
- **08** SQLite local com extensão opcional; PostgreSQL/MySQL como referência.
- **09** Parquet offline, extensões e política de secrets; sem acesso cloud.
- **10** Parquet particionado e limites versus Iceberg/Delta; não implementa commits Iceberg/Delta.
- **11** SQL em camadas e projeto dbt mínimo gerado; sem execução dbt automática.
- **12** Zonemaps, ART e interpretação de planos.
- **13** EXPLAIN/ANALYZE, fundamentos de out-of-core; não comprova spill.
- **14** Pandas/Arrow local e comparação de Wasm/MotherDuck; sem implantação remota.

## Nota de preservação editorial
Este pacote é uma **nova edição didática**, não uma modificação linha a linha dos originais. Os capítulos 05 e 06 tinham material mais extenso no GitHub; preserve as versões originais para comparar quaisquer experiências ou explicações avançadas antes de substituí-las em definitivo.

### Verificação de substituição
Os nomes `.ipynb` do ZIP correspondem aos nomes dos capítulos já existentes. Faça backup antes de substituir; `git status` e `git diff` podem mostrar exatamente o que mudou. Os laboratórios ainda dependem de validação real no kernel local.
