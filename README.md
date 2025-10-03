# 📊 Bank Marketing Dataset – Análise de Dados com Python

Este projeto tem como objetivo **praticar análise de dados em Python** utilizando o dataset público [Bank Marketing Dataset](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset).  
A base contém informações de campanhas de marketing direto de uma instituição bancária, permitindo explorar perfis de clientes, taxas de adesão e fatores que influenciam na contratação de depósitos a prazo.

---

## 🚀 Etapas do Projeto

### 1. Exploração Inicial (Análise Descritiva)
- Quantidade de clientes participantes da campanha.  
- Idade média, mínima e máxima.  
- Saldo médio em conta.  
- Percentual de clientes que contrataram o depósito (`deposit = yes`).  
- Contagem de clientes por profissão (`job`).  

### 2. Análise de Segmentos (Perfis de Cliente)
- Taxa de adesão ao depósito por faixa etária (18-30, 31-45, 46-60, 60+).  
- Comparação da taxa de adesão entre solteiros, casados e divorciados.  
- Impacto de possuir empréstimo pessoal (`loan`) na adesão.  
- Diferença no saldo médio entre quem contratou e quem não contratou.  
- Ranking de profissões com maior taxa de adesão.  

### 3. Visualizações (Matplotlib / Seaborn)
- Histograma da idade dos clientes.  
- Boxplot do saldo por estado civil.  
- Gráfico de barras da taxa de adesão por profissão.  
- Heatmap de correlação entre variáveis numéricas.  
- Linha mostrando adesão mensal.  

### 4. Insights de Negócio
- **Duração da ligação (`duration`)** influencia a adesão?  
- Qual o **melhor canal de contato (`contact`)** para novas campanhas?  

---

## 🛠️ Tecnologias Utilizadas
- **Python 3**  
- [Pandas](https://pandas.pydata.org/)  
- [NumPy](https://numpy.org/)  
- [Matplotlib](https://matplotlib.org/)  
- [Seaborn](https://seaborn.pydata.org/)  
- Jupyter Notebook / VS Code
- Linux/Ubuntu 

---

## 🎯 Objetivos do Projeto
- Reforçar conceitos de **estatística descritiva, análise exploratória e storytelling com dados**.  
- Praticar o uso de bibliotecas do ecossistema Python aplicadas à **Data Science**.  
- Simular um cenário real de análise de campanhas de marketing em instituições financeiras.  

---

## 📂 Estrutura do Projeto
```bash
├── 01_base/              # Arquivos de dados (dataset)
├── 02_scripts/           # Scripts em Python
├── 03_saida/             # Gráficos e visualizações exportadas
└── README.md             # Documentação do projeto
