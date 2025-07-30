# 🛒 Supermarket Sales Forecast

Este projeto tem como objetivo prever o valor total de vendas em um supermercado com base em variáveis como tipo de produto, horário da compra, gênero do cliente, entre outros. Utilizamos um modelo de Machine Learning com Random Forest para criar uma previsão robusta e precisa.

---

## 📁 Estrutura do Projeto

```
supermarket-sales-forecast/
├── data/
│   └── Dados.csv
├── images/
│   ├── heatmap_correlacao.png
│   └── total_vendas_produto.png
├── src/
│   └── vendas_model_rf.ipynb
├── README.md
└── requirements.txt
```

---

## 🔍 Problema

Prever a coluna `Total` de uma venda no supermercado com base em variáveis relacionadas ao produto, cliente, localização, data e hora.

---

## ⚙️ Tecnologias Utilizadas

- Python 3.10+
- Pandas
- Numpy
- Seaborn
- Matplotlib
- Scikit-Learn

---

## 🚀 Etapas do Projeto

1. **Importação e análise dos dados**
2. **Pré-processamento:**
   - Conversão de datas e extração de hora
   - Criação de variáveis como `Part_of_Day`, `Is_Weekend`
3. **Feature Engineering:**
   - Ticket médio por linha de produto
   - Label Encoding para variáveis categóricas
4. **Divisão dos dados em treino e teste**
5. **Treinamento de um modelo Random Forest Regressor**
6. **Avaliação do modelo com MSE e R²**
7. **Visualização das features mais importantes**
8. **Geração de gráficos salvos em `images/`**

---

## 📈 Resultados

- **MSE (Erro Quadrático Médio):** 102.3436
- **R² (Coeficiente de Determinação):** 0.9984
- **Features mais importantes:**
  - Quantity, Unit Price, Rating

---

## 📊 Gráficos Gerados

- `total_vendas_produto.png`: Total de vendas por linha de produto
- `heatmap_correlacao.png`: Correlação entre variáveis numéricas

---

## 📬 Contato

Desenvolvido por [Leonardo Coelho](https://github.com/LeonardCoelho) 🚀
