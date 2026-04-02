# 📊 Funções Básicas do Excel (SOMA, MÉDIA, MÁXIMO, MÍNIMO e SE)

Este material tem como objetivo ensinar, de forma clara e prática, as principais funções do Excel utilizadas no ambiente profissional.

---

# 🧠 Por que aprender essas funções?

Antes de ir para a prática, é importante entender:

Essas funções são a base de praticamente **todas as análises de dados no Excel**. Elas permitem:

* Organizar informações
* Tomar decisões com base em dados
* Automatizar cálculos repetitivos
* Criar relatórios profissionais

---

# 📋 Base de Dados (Planilha para Aula)

Use esta tabela como exemplo principal:

| Funcionário | Vendas Jan | Vendas Fev | Vendas Mar | Total | Média | Maior Venda | Menor Venda | Desempenho |
| ----------- | ---------- | ---------- | ---------- | ----- | ----- | ----------- | ----------- | ---------- |
| Ana         | 1200       | 1500       | 1700       |       |       |             |             |            |
| João        | 800        | 950        | 700        |       |       |             |             |            |
| Maria       | 2000       | 2100       | 1900       |       |       |             |             |            |
| Carlos      | 500        | 650        | 600        |       |       |             |             |            |

---

# 📌 1. Função SOMA

### 🔎 O que ela faz?

A função SOMA adiciona valores. É usada para calcular totais.

### 💡 Aplicação na tabela:

Calcular o total de vendas por funcionário.

### 🧾 Fórmula:

```excel
=SOMA(B2:D2)
```

### 📖 Explicação:

* B2:D2 → intervalo das vendas (Jan, Fev, Mar)
* Resultado → soma de todos os meses

👉 Arraste a fórmula para os demais funcionários.

---

# 📌 2. Função MÉDIA

### 🔎 O que ela faz?

Calcula o valor médio de um conjunto de números.

### 💡 Aplicação:

Descobrir a média de vendas mensal.

### 🧾 Fórmula:

```excel
=MÉDIA(B2:D2)
```

### 📖 Explicação:

* Soma os valores e divide pela quantidade de meses
* Muito usada para análise de desempenho

---

# 📌 3. Função MÁXIMO

### 🔎 O que ela faz?

Retorna o maior valor dentro de um conjunto.

### 💡 Aplicação:

Identificar o melhor mês de vendas.

### 🧾 Fórmula:

```excel
=MÁXIMO(B2:D2)
```

### 📖 Explicação:

* Mostra o pico de desempenho
* Ajuda a identificar padrões positivos

---

# 📌 4. Função MÍNIMO

### 🔎 O que ela faz?

Retorna o menor valor de um conjunto.

### 💡 Aplicação:

Identificar o pior mês de vendas.

### 🧾 Fórmula:

```excel
=MÍNIMO(B2:D2)
```

### 📖 Explicação:

* Mostra pontos de melhoria
* Importante para análise crítica

---

# 📌 5. Função SE

### 🔎 O que ela faz?

Toma decisões com base em uma condição.

### 💡 Aplicação:

Classificar o desempenho do funcionário.

### 🎯 Regra de negócio:

* Média ≥ 1500 → "Alto Desempenho"
* Média ≥ 1000 → "Médio Desempenho"
* Média < 1000 → "Baixo Desempenho"

### 🧾 Fórmula:

```excel
=SE(F2>=1500; "Alto"; SE(F2>=1000; "Médio"; "Baixo"))
```

### 📖 Explicação:

* F2 → célula da média
* Testa condições em sequência
* Retorna um texto conforme o resultado

---

# 🧪 Resultado Esperado (Após Aplicar Fórmulas)

| Funcionário | Total | Média | Maior | Menor | Desempenho |
| ----------- | ----- | ----- | ----- | ----- | ---------- |
| Ana         | 4400  | 1466  | 1700  | 1200  | Médio      |
| João        | 2450  | 816   | 950   | 700   | Baixo      |
| Maria       | 6000  | 2000  | 2100  | 1900  | Alto       |
| Carlos      | 1750  | 583   | 650   | 500   | Baixo      |

---

# 💼 Conexão com o Mercado de Trabalho

Essas funções são usadas diariamente em:

### 📊 Empresas e Escritórios

* Relatórios de desempenho
* Controle de metas
* Consolidação de dados

### 💰 Área Financeira

* Soma de receitas/despesas
* Análise de médias mensais
* Identificação de picos de gastos

### 📈 Vendas

* Avaliação de vendedores
* Comparação de resultados
* Tomada de decisão estratégica

---

# 🎯 Dicas Didáticas para Aula

✔ Comece com cálculo manual antes da fórmula
✔ Mostre erro comum (ex: selecionar intervalo errado)
✔ Peça para alunos alterarem valores e observarem mudanças
✔ Trabalhe com perguntas:

* Quem vendeu mais?
* Quem precisa melhorar?
* Qual foi o melhor mês?

---

# 🚀 Exercícios Propostos

1. Adicione uma coluna de **Bônus**:

   * Se média ≥ 1500 → bônus de 10%
   * Caso contrário → 0%

2. Descubra:

   * Total geral da empresa
   * Média geral

3. Crie uma nova regra:

   * Se total > 5000 → "Destaque"

---

# 📚 Conclusão

Essas funções formam a base do Excel profissional.
Quem domina esses conceitos consegue:

* Trabalhar com dados reais
* Automatizar tarefas
* Gerar valor dentro das empresas

---

Se quiser, posso agora:

* Criar o **arquivo Excel pronto para download**
* Montar uma **lista de exercícios progressivos**
* Ou transformar isso em **aula completa com roteiro de ensino**
