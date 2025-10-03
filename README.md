# 📝 **Exercícios**

## **1. Exploração Inicial dos Dados (Análise Descritiva)**

* 📌 **Exercício 1:** Quantos clientes participaram da campanha?
* 📌 **Exercício 2:** Idade média, mínima e máxima dos clientes.
* 📌 **Exercício 3:** Qual o saldo médio em conta?
* 📌 **Exercício 4:** Percentual de clientes que contrataram o depósito (`deposit = yes`).
* 📌 **Exercício 5:** Contagem de clientes por profissão (`job`).

---

## **2. Análise de Segmentos (Perfis de Cliente)**


* 📌 **Exercício 6:** Taxa de adesão ao depósito por faixa etária (ex.: 18-30, 31-45, 46-60, 60+).
* 📌 **Exercício 7:** Comparar taxa de adesão entre solteiros, casados e divorciados.
* 📌 **Exercício 8:** Verificar se quem já tinha **empréstimo pessoal (`loan`)** respondeu mais ou menos à campanha.
* 📌 **Exercício 9:** Analisar o saldo médio de quem contratou vs quem não contratou.
* 📌 **Exercício 10:** Ranking de profissões com maior taxa de adesão.

---

## **3. Visualizações (Matplotlib / Seaborn)**


* 📊 **Exercício 11:** Histograma da idade dos clientes.
* 📊 **Exercício 12:** Boxplot do saldo por estado civil.
* 📊 **Exercício 13:** Gráfico de barras da taxa de adesão (`deposit`) por profissão.
* 📊 **Exercício 14:** Heatmap de correlação entre as variáveis numéricas (`age, balance, duration, campaign, pdays, previous`).
* 📊 **Exercício 15:** Linha mostrando adesão mensal (quantos contrataram em cada `month`).

---

## **4. Insights para Estratégia de Marketing**


* 📌 **Exercício 16:** Quem respondeu melhor à campanha: clientes com ou sem financiamento habitacional (`housing`)?
* 📌 **Exercício 17:** Duração da ligação (`duration`) influencia a adesão? Mostrar em gráfico.
* 📌 **Exercício 18:** Qual o melhor canal de contato (`contact`) para novas campanhas?
* 📌 **Exercício 19:** Existe relação entre número de contatos anteriores (`previous`) e adesão?
* 📌 **Exercício 20:** Montar um relatório curto com **3 perfis ideais de clientes** para focar na próxima campanha.

---

## **5. Mini Painel no Streamlit**


* KPIs no topo:

  * Total de clientes
  * Taxa geral de adesão
  * Idade média
  * Saldo médio

* Filtros: profissão, estado civil, idade.

* Gráficos:

  * Distribuição da idade (histograma).
  * Adesão por profissão (barras).
  * Adesão por mês (linha).
  * Boxplot de saldo por adesão.

* Tabela dinâmica: listar **top 20 clientes com maior saldo que não aderiram**, para direcionar no próximo contato.

