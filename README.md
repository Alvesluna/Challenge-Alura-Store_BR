# 🏪 Análise Alura Store - Python para Data Science

[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Status](https://img.shields.io/badge/status-concluído-brightgreen)](https://github.com/Alvesluna/Challenge-Alura-Store_BR)

Análise estratégica de desempenho de uma rede de lojas fictícia, desenvolvida como parte do **Challenge Alura Store** da formação Python para Data Science.

## 📊 Propósito da Análise

Esta análise tem como objetivo avaliar o desempenho de 4 lojas de uma rede varejista, utilizando métricas de negócio para identificar a **unidade com menor performance estratégica** e que seria a **melhor candidata para venda**. A decisão é baseada em um sistema de pontuação que combina:

- **Faturamento total**
- **Satisfação do cliente** (avaliação média)
- **Eficiência operacional** (custo do frete como percentual do faturamento)

## 📁 Estrutura do Projeto

## 🔍 Insights e Resultados Principais

### 🎯 Conclusão Estratégica

**Loja Recomendada para Venda:** **Loja 1**

### 📈 Principais Motivos:

| Métrica               | Loja 1          | Posição      | Implicação                      |
| --------------------- | --------------- | ------------ | ------------------------------- |
| **Faturamento Total** | R$ 1.534.509,12 | 4ª (menor)   | Menor retorno financeiro        |
| **Avaliação Média**   | 3,98/5,0        | 4ª (pior)    | Menor satisfação do cliente     |
| **Frete/Faturamento** | 5,33%           | 1ª (maior %) | Maior impacto na margem líquida |
| **Score Total**       | Mais baixo      | 4ª           | Pior desempenho combinado       |

### 📊 Exemplo de Análise Visual

A análise inclui visualizações como:

1. **Comparativo de Faturamento por Loja** - Gráfico de barras mostrando a hierarquia de receita
2. **Distribuição de Avaliação dos Clientes** - Boxplot comparando a satisfação entre lojas
3. **Impacto Percentual do Frete** - Gráfico de pizza ou barras mostrando custo operacional
4. **Score Final de Desempenho** - Ranking visual das lojas baseado no sistema de pontuação

**Insight Visual:** A Loja 1 consistentemente aparece na última posição em todos os gráficos comparativos, destacando-se como a unidade de desempenho mais fraco.

## 🚀 Como Executar a Análise

### Pré-requisitos

- Python 3.8 ou superior
- Gerenciador de pacotes `pip`

### Instalação

1. **Clone o repositório:**

```bash
git clone https://github.com/Alvesluna/Challenge-Alura-Store_BR.git
cd Challenge-Alura-Store_BR
pip install -r requirements.txt
jupyter notebook AluraStoreBrasil.ipynb
Dependências Principais
O arquivo requirements.txt inclui:

pandas - Manipulação de dados

numpy - Operações numéricas

matplotlib e seaborn - Visualizações gráficas

jupyter - Ambiente interativo

📋 Metodologia Analítica
Coleta e Limpeza: Carregamento e tratamento dos dados de vendas

Análise Descritiva: Cálculo de métricas-chave por loja

Sistema de Pontuação: Desenvolvimento de algoritmo para ranking

Visualização: Criação de gráficos para comunicação dos insights

Recomendação: Conclusão baseada em evidências quantitativas

🎯 Tomada de Decisão Baseada em Dados
A recomendação de vender a Loja 1 baseia-se no princípio de otimização de portfólio, onde recursos seriam realocados para as unidades com:

Maior retorno sobre investimento (Loja 3 e 4)

Melhor relação com clientes (maior fidelização potencial)

Maior eficiência operacional (menor custo relativo)

📄 Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para detalhes.
```
