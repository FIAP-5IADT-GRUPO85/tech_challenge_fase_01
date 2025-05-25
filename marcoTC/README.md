# Tech Challenge - Fase 1
Previsão de Custos Médicos com Regressão Linear

## 💡 Descrição
Este projeto tem como objetivo prever o custo do seguro de saúde de um paciente com base em variáveis como idade, sexo, índice de massa corporal (IMC), número de filhos, tabagismo e região de residência.

## 📁 Dataset
O dataset utilizado é o `simulated_insurance_100k.csv`, contendo 100.000 registros com as seguintes variáveis:
- `age`: idade do paciente
- `sex`: gênero
- `bmi`: índice de massa corporal
- `children`: número de filhos
- `smoker`: se o paciente é fumante
- `region`: região nos EUA
- `charges`: custo do seguro (variável alvo)

## 🔍 Etapas do Projeto
1. **Exploração de dados**
2. **Pré-processamento e codificação**
3. **Divisão treino/teste**
4. **Modelagem com Regressão Linear**
5. **Avaliação com métricas e regressão OLS**
6. **Visualização: valores reais vs previstos**

## 🛠️ Tecnologias e bibliotecas
- Python
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
- Statsmodels

## 📊 Resultado
- R² ≈ 0.78
- MAE ≈ 4186
- O modelo apresenta boa capacidade preditiva, com impacto significativo da variável "fumante" no custo final.

## 📓 Notebook
➡️ [`tech_challenge_fase1.ipynb`](./tech_challenge_fase1.ipynb)

## 📽️ Vídeo explicativo
[link_do_video] *(substituir após publicação no YouTube)*
