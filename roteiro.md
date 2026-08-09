# Roteiro de Trabalho — Mini-Projeto Avaliativo

## Análise Exploratória da Base Varejo

> **Fonte de verdade:** edital do Mini-Projeto Avaliativo — Módulo 1 — Semana 07.
>
> O documento "Projeto III — Análise Exploratória de Dados" será utilizado apenas como
> referência sobre a base e seu contexto. Suas exigências não fazem parte do escopo
> obrigatório deste projeto.

---

## 🎯 Objetivo

Realizar uma Análise Exploratória de Dados (AED) da base `Varejo.csv`,
aplicando etapas de inspeção, tratamento, transformação, estatística descritiva
e agrupamento, produzindo conclusões objetivas sobre os dados.

---

# 🧭 ROTEIRO

## Sprint 0 — Planejamento

- [ ] Ler e interpretar o edital
- [ ] Transformar os requisitos em checklist
- [ ] Conferir a estrutura do projeto no VS Code
- [ ] Confirmar localização da base `Varejo.csv`
- [ ] Definir o fluxo da análise

---

## Sprint 1 — Importação e reconhecimento dos dados

- [ ] Importar a base com `pandas`
- [ ] Verificar número de registros
- [ ] Verificar número e nomes das colunas
- [ ] Verificar tipos de dados
- [ ] Visualizar os primeiros registros
- [ ] Obter uma visão inicial da estrutura da base

**Resultado esperado:** fotografia inicial da base.

---

## Sprint 2 — Transformação e tipos de dados

- [ ] Identificar tipos que precisam de ajuste
- [ ] Verificar strings, inteiros e demais tipos relevantes
- [ ] Verificar a coluna `DATA`
- [ ] Converter `DATA` para `datetime`
- [ ] Validar a conversão
- [ ] Registrar problemas encontrados

**Resultado esperado:** dados com tipos adequados para a análise.

---

## Sprint 3 — Qualidade e limpeza dos dados

### Valores nulos

- [ ] Verificar nulos por coluna
- [ ] Identificar quais colunas apresentam problemas
- [ ] Definir o tratamento adequado
- [ ] Aplicar o tratamento
- [ ] Justificar a escolha

### Duplicatas

- [ ] Verificar registros duplicados
- [ ] Avaliar se são duplicatas relevantes
- [ ] Remover quando necessário
- [ ] Conferir o resultado

### Categorias

- [ ] Verificar categorias vazias/inconsistentes
- [ ] Tratar categorias vazias quando necessário
- [ ] Utilizar `Sem Categoria` quando aplicável
- [ ] Validar o resultado

### Regras de negócio

- [ ] Verificar a regra do identificador da compra
- [ ] Validar `CO_ID`
- [ ] Conferir possíveis inconsistências

**Resultado esperado:** base limpa e validada.

---

## Sprint 4 — Estatística descritiva

### Variável obrigatória: `CL_FHL`

Número de filhos do cliente.

Calcular:

- [ ] Contagem
- [ ] Média
- [ ] Mediana
- [ ] Desvio padrão
- [ ] Moda
- [ ] Mínimo
- [ ] Máximo

**Resultado esperado:** resumo estatístico da variável `CL_FHL`.

---

## Sprint 5 — Agrupamentos e análise

Realizar pelo menos **dois agrupamentos**, utilizando
`groupby()` ou `pivot_table()`.

### Agrupamento 1

- [ ] Definir pergunta
- [ ] Realizar agrupamento
- [ ] Interpretar resultado

### Agrupamento 2

- [ ] Definir pergunta
- [ ] Realizar agrupamento
- [ ] Interpretar resultado

**Resultado esperado:** identificação de padrões relevantes nos dados.

---

## Sprint 6 — Conclusões e documentação

### Insights

Produzir de **3 a 6 conclusões** contendo:

- [ ] Principais descobertas
- [ ] Padrões identificados
- [ ] Resultados relevantes dos agrupamentos
- [ ] Possíveis problemas remanescentes na base

### README

- [ ] Descrever o projeto
- [ ] Explicar o objetivo
- [ ] Registrar a metodologia utilizada
- [ ] Registrar os principais insights
- [ ] Incluir reflexão sobre ETL e qualidade dos dados

---

# 📦 Entrega final

## Código

- [ ] Arquivo `.py` ou `.ipynb`
- [ ] Código executável
- [ ] Lógica organizada
- [ ] Etapas claramente identificadas
- [ ] Tratamentos documentados de forma objetiva

## GitHub

- [ ] Repositório público
- [ ] Pasta seguindo o padrão do projeto
- [ ] Código inserido
- [ ] `README.md`
- [ ] `README_NomeDoAluno_Turma.md`
- [ ] Base/arquivo tratado conforme definido no projeto
- [ ] Versionamento realizado

## Submissão

- [ ] Conferir estrutura final do repositório
- [ ] Conferir se todos os arquivos abrem corretamente
- [ ] Conferir README
- [ ] Conferir código do início ao fim
- [ ] Submeter link do GitHub no AVA
- [ ] Prazo: **17/08/2026 às 22h**

---

# ✅ Checklist da Rubrica

| Critério | Status |
|---|---|
| Versionamento / GitHub | ⬜ |
| Documentação / README | ⬜ |
| Manipulação da base CSV | ⬜ |
| Tratamento de nulos e condicionais | ⬜ |
| Regras de negócio e datas | ⬜ |
| Pelo menos 2 agrupamentos | ⬜ |
| Estatísticas de `CL_FHL` | ⬜ |

---

# 🧠 Regra do projeto

> **Primeiro entender os dados.  
> Depois tratar.  
> Depois analisar.  
> Por fim, interpretar.**

Não realizar transformações ou análises apenas para "cumprir tabela".
Cada etapa deve ter uma finalidade clara dentro da análise.