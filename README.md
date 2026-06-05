# 📊 Uplift Modeling para Retenção de Clientes

Este projeto utiliza técnicas avançadas de **Uplift Modeling** (Causal Inference) para otimizar campanhas de marketing de retenção. O objetivo é identificar quais clientes são verdadeiramente influenciados por uma campanha, diferenciando-os daqueles que permaneceriam espontaneamente.

## 🚀 Objetivo do Projeto
Diferenciar quatro perfis de clientes:
1. **Persuasíveis (Persuadables):** Só retêm se receberem a campanha.
2. **Causas Perdidas (Lost Causes):** Não retêm, mesmo com a campanha.
3. **Garantidos (Sure Things):** Retêm mesmo sem a campanha.
4. **Cães Adormecidos (Sleeping Dogs):** Podem cancelar se forem incomodados.

## 🛠️ Tecnologias e Bibliotecas
- **Python 3.10+**
- **Pandas & Numpy:** Manipulação de dados e engenharia de atributos.
- **Plotly:** Storytelling visual e gráficos interativos.
- **Scikit-Learn:** Modelagem de Machine Learning (T-Learner).
- **Algoritmos Comprimidos:** Naive Bayes, Regressão Logística, Random Forest e Gradient Boosting.

## 📈 Etapas de Desenvolvimento
- [x] **EDA Completa:** Análise univariada, bivariada e multivariada com teste de balanceamento.
- [x] **Feature Engineering:** Criação de 7 novas métricas de negócio (Renda por idade, score fidelidade, etc).
- [x] **Machine Learning:** Implementação do T-Learner com 4 famílias de algoritmos para comparação.
- [x] **Métricas Avançadas:** Avaliação por AUC, Precision, Recall e KS (Kolmogorov-Smirnov).
- [x] **ROI Simulado:** Cálculo financeiro de economia ao evitar disparos desnecessários.

## 📂 Como executar
1. Clone este repositório.
2. Instale as dependências: `pip install -r requirements.txt`
3. Abra o arquivo `Projeto_Uplift_Modeling.ipynb` no VSCode ou Jupyter Notebook.

---
*Projeto desenvolvido como estudo de Data Science voltado para Marketing Analytics.*
