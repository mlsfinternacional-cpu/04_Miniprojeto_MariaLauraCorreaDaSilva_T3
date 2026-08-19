# Roteiro de Trabalho — Mini-Projeto Avaliativo

## Análise Exploratória da Base Varejo

> **Fonte de verdade:** edital do Mini-Projeto Avaliativo — Módulo 1 — Semana 07.
>
> O documento "Projeto III — Análise Exploratória de Dados" será utilizado apenas como
> referência sobre a base e seu contexto. Suas exigências não fazem parte do escopo
> obrigatório deste projeto.

---

## Objetivo

Realizar uma Análise Exploratória de Dados (AED) da base `Varejo.csv`,
aplicando etapas de inspeção, tratamento, transformação, estatística descritiva
e agrupamento, produzindo conclusões objetivas sobre os dados.

---

# ROTEIRO

## Sprint 0 — Planejamento

- [X] Ler e interpretar o edital
- [X] Transformar os requisitos em checklist
- [X] Conferir a estrutura do projeto no VS Code
- [X] Confirmar localização da base `Varejo.csv`
- [X] Definir o fluxo da análise

---

## Sprint 1 — Importação e reconhecimento dos dados

- [X] Importar a base com `pandas`
- [X] Verificar número de registros
- [X] Verificar número e nomes das colunas
- [X] Verificar tipos de dados
- [X] Visualizar os primeiros registros
- [X] Obter uma visão inicial da estrutura da base

**Resultado esperado:** fotografia inicial da base.

---

## Sprint 2 — Transformação e tipos de dados

- [X] Identificar tipos que precisam de ajuste
- [X] Verificar strings, inteiros e demais tipos relevantes
- [X] Verificar a coluna `DATA`
- [X] Converter `DATA` para `datetime`
- [X] Validar a conversão
- [X] Registrar problemas encontrados

**Resultado esperado:** dados com tipos adequados para a análise.

---

## Sprint 3 — Qualidade e limpeza dos dados

### Valores nulos

- [X] Verificar nulos por coluna
- [X] Identificar quais colunas apresentam problemas
- [X] Definir o tratamento adequado
- [X] Aplicar o tratamento
- [X] Justificar a escolha

### Duplicatas

- [X] Verificar registros duplicados
- [X] Avaliar se são duplicatas relevantes
- [X] Remover quando necessário
- [X] Conferir o resultado

### Categorias

- [X] Verificar categorias vazias/inconsistentes
- [X] Tratar categorias vazias quando necessário
- [X] Utilizar `Sem Categoria` quando aplicável
- [X] Validar o resultado

### Regras de negócio

- [X] Verificar a regra do identificador da compra
- [X] Validar `CO_ID`
- [X] Conferir possíveis inconsistências

**Resultado esperado:** base limpa e validada.

---

## Sprint 4 — Estatística descritiva

### Variável obrigatória: `CL_FHL`

Número de filhos do cliente.

Calcular:

- [X] Contagem
- [X] Média
- [X] Mediana
- [X] Desvio padrão
- [X] Moda
- [X] Mínimo
- [X] Máximo

**Resultado esperado:** resumo estatístico da variável `CL_FHL`.

---

## Sprint 5 — Agrupamentos e análise

Realizar pelo menos **dois agrupamentos**, utilizando
`groupby()` ou `pivot_table()`.

### Agrupamento 1

- [X] Definir pergunta
- [X] Realizar agrupamento
- [X] Interpretar resultado

### Agrupamento 2

- [X] Definir pergunta
- [X] Realizar agrupamento
- [X] Interpretar resultado

**Resultado esperado:** identificação de padrões relevantes nos dados.

---

### Conclusões Insghts e Documentação

### Insights

Produzir de **3 a 6 conclusões** contendo:

- [X] Principais descobertas
- [X] Padrões identificados
- [X] Resultados relevantes dos agrupamentos
- [X] Possíveis problemas remanescentes na base

### README

- [X] Descrever o projeto
- [X] Explicar o objetivo
- [X] Registrar a metodologia utilizada
- [X] Registrar os principais insights
- [X] Incluir reflexão sobre ETL e qualidade dos dados

---
## Sprint 6- Entrega Final

### Código

- [X] Arquivo `.py` ou `.ipynb`
- [X] Código executável
- [X] Lógica organizada
- [X] etapas claramente identificadas
- [X] Tratamentos documentados de forma objetiva

### Github

- [X] Repositório público
- [X] Pasta seguindo o padrão do projeto
- [X] Código inserido
- [X] `README.md`
- [X] `README_NomeDoAluno_Turma.md`
- [X] Base/arquivo tratado conforme definido no projeto
- [X] Versionamento realizado

### Submissão

- [X] Conferir estrutura final do repositório
- [X] Conferir se todos os arquivos abrem corretamente
- [X] Conferir README
- [X] Conferir código do início ao fim
- [X] Submeter link do GitHub no AVA
- [X] Prazo: **17/08/2026 às 22h**

---

# Checklist da Rubrica

| Critério | Status |
|---|---|
| Versionamento / GitHub | OK |
| Documentação / README | OK |
| Manipulação da base CSV | OK |
| Tratamento de nulos e condicionais | OK |
| Regras de negócio e datas | OK |
| Pelo menos 2 agrupamentos | OK |
| Estatísticas de `CL_FHL` | OK |

---

# Regra do projeto

> **Primeiro entender os dados.  
> Depois tratar.  
> Depois analisar.  
> Por fim, interpretar.**

Não realizar transformações ou análises apenas para "cumprir tabela".
Cada etapa deve ter uma finalidade clara dentro da análise.
