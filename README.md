# Rendimento Mensal vs. Escolaridade: Análise de Dados e Regressão Linear

Projecto final da cadeira **Fundamentos de Ciência de Dados e Big Data** (ISCET), desenvolvido em Python com Jupyter Notebook.

## Objectivo
Analisar a relação entre o **rendimento mensal** de agregados familiares e duas variáveis explicativas: **anos de escolaridade** e **número de membros activos** (trabalhadores no agregado). No final, construir um modelo de regressão linear para prever o rendimento.

## Dados
`Base_Rendimento.xlsx`: 41 registos (ID, Anos de Escolaridade, Membros Activos, Rendimento Mensal), fornecida pelo docente.

## Etapas do projecto
1. **Limpeza de dados**: identificação e remoção de duplicados e de valores em falta, e conversão de tipos (inteiros para escolaridade e membros activos, float para rendimento).
2. **Análise exploratória**: estatísticas descritivas, histogramas, gráficos de dispersão, matriz de correlação (heatmap) e um dashboard com 6 gráficos.
3. **Modelação**: regressão linear com divisão 80% treino / 20% teste (`random_state=42`).
4. **Previsão**: estimativa do rendimento para um novo agregado (16 anos de escolaridade e 2 membros activos).

## Principais resultados
- Forte correlação entre escolaridade e rendimento (r ≈ 0,98).
- Modelo com **R² ≈ 0,98** no conjunto de teste.
- Cada ano adicional de escolaridade está associado a um aumento de cerca de **1 713 MT** no rendimento mensal.
- Rendimento previsto para o caso de teste: ≈ **27 428 MT**.

## Tecnologias
Python · pandas · NumPy · openpyxl · Matplotlib · Seaborn · scikit-learn

## Ficheiros
- `Gaspar_Bendzane_Meu_Projeto_Final_Fundamentos_Ciencia_de_Dados.ipynb`: notebook com todo o código
- `Base_Rendimento.xlsx`: base de dados utilizada

## Autor
Gaspar Tomás Bendzane
