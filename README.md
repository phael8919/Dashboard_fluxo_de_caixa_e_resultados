# Dashboard de Fluxo de Caixa no Power BI para Download

Autor: Raphael Vieira  
Publicado em: 15 de maio de 2026

Você gostaria de acompanhar as entradas e saídas de caixa? E mais do que isso: acompanhar detalhadamente quais são seus principais clientes e quais são suas principais despesas? Saber qual é o seu resultado mensal?

Neste artigo, disponibilizo para download um dashboard em Power BI com:

- Fluxo de Caixa
- Resultado Mensal
- Análise de Receitas
- Análise de Despesas

---

## Como baixar o Dashboard

O download está dividido em duas partes:

1. Base de dados (Excel)
2. Dashboard (Power BI)

### Downloads

- [Base de dados (Excel)](https://www.mediafire.com/)
- [Dashboard Power BI](https://www.mediafire.com/)

> **Observação:** Para o dashboard funcionar corretamente e atualizar os dados, é necessário baixar também a base de dados.

---

## Como utilizar e atualizar o dashboard

Caso não queira ler o artigo completo, há também um tutorial no YouTube:

- [Tutorial no YouTube](https://youtu.be/)

---

# Base de Dados

Antes de utilizar o dashboard, é necessário preencher a base de dados. Ela é composta por 4 abas:

- Validações
- Receitas
- Despesas
- Datas

---

## Aba "Validações"

A aba possui cinco colunas:

| Coluna | Descrição |
|---|---|
| `SITUACAO_RECEITA` | Situação da receita |
| `CLIENTE` | Nome dos clientes |
| `SITUACAO_DESPESA` | Situação da despesa |
| `TIPO_DESPESA` | Tipo da despesa |
| `FORNECEDOR` | Nome dos fornecedores |

### Exemplos de preenchimento

- Receita a receber
- Receita recebida
- Previsão de receita
- Despesa a pagar
- Despesa paga

> Você pode utilizar os nomes que preferir.

### Observação

Caso sejam digitados valores repetidos em alguma coluna, a planilha destacará automaticamente os valores duplicados em amarelo.

É recomendado não repetir valores nas colunas da aba **Validações**.

---

## Aba "Receitas"

Nesta aba são cadastradas as receitas com os seguintes campos:

| Campo |
|---|
| DATA |
| SITUACAO |
| CLIENTE |
| VALOR_RECEITA |

### Observação

As colunas `SITUACAO` e `CLIENTE` possuem validação de dados proveniente da aba **Validações**.

---

## Aba "Despesas"

Nesta aba são cadastradas as despesas com os seguintes campos:

| Campo |
|---|
| DATA |
| SITUACAO |
| TIPO_DESPESA |
| FORNECEDOR |
| VALOR_DESPESA |

### Observação

As colunas:

- `SITUACAO`
- `TIPO_DESPESA`
- `FORNECEDOR`

possuem validação de dados proveniente da aba **Validações**.

---

## Aba "Datas"

A aba Datas contém uma validação de datas utilizada como filtro no dashboard.

Caso necessário, é possível incluir novas datas para utilização nos filtros.

---

# Como conectar a base de dados ao Dashboard no Power BI

Para conectar a base de dados:

1. Vá em:
   - **Página Inicial**
   - **Obter Dados**
   - **Configurações da Fonte de Dados**

2. Clique em:
   - **Alterar fonte**

3. Depois:
   - Clique em **Procurar...**
   - Informe o local onde o arquivo da base está salvo
   - Clique em **OK**

---

# Utilizando o Dashboard

O dashboard é dividido em 5 abas:

1. Menu
2. Fluxo de Caixa
3. Resultado Mensal
4. Análise das Receitas
5. Análise das Despesas

---

## Aba "Menu"

A primeira aba possui:

- Links para navegação entre as páginas
- Link para o LinkedIn do autor
- Link para o canal no YouTube

---

## Aba "Fluxo de Caixa"

O painel possui 6 gráficos que demonstram:

- Entradas
- Saídas
- Saldos
- Top 5 clientes
- Top 5 despesas

### Filtros

Os filtros ficam no canto superior direito do dashboard.

### Navegação

Para voltar ao menu:

```text
CTRL + Clique no símbolo "$"
```

### Visualização de saldos diários

Para visualizar somente os saldos:

```text
CTRL + Clique em "VER SOMENTE SALDO"
```

Para voltar ao fluxo de caixa:

```text
CTRL + Clique em "VER FLUXO DE CAIXA"
```

---

## Aba "Resultado Mensal"

O painel procura demonstrar o resultado mensal da empresa, utilizando um formato semelhante ao painel de fluxo de caixa.

---

## Aba "Análise das Receitas"

Esta aba demonstra:

- Faturamento mensal
- Curva ABC de clientes
- Principais clientes
- Classe de cada cliente

---

## Aba "Análise das Despesas"

Nesta aba é possível visualizar:

- Principais fornecedores
- Histórico mensal das despesas
- Curva ABC por tipo de despesa

---

# Considerações Finais

Este dashboard foi desenvolvido para facilitar o acompanhamento financeiro e fornecer uma visão mais analítica sobre receitas, despesas, clientes e fornecedores.

Com ele, é possível:

- Monitorar fluxo de caixa
- Analisar resultados mensais
- Identificar principais clientes
- Avaliar principais despesas
- Aplicar análises ABC

---

## Artigo original

[Artigo no LinkedIn](https://www.linkedin.com/pulse/dashboard-de-fluxo-caixa-power-bi-para-download-raphael-vieira-vrnzf/)
