# Predição de Resistência do Concreto usando Machine Learning
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)

## 📊 Sobre o Projeto
Este projeto implementa um modelo de machine learning para prever a resistência à compressão do concreto utilizando técnicas de regressão linear. A análise foi desenvolvida utilizando Python e suas principais bibliotecas de ciência de dados.

### 🎯 Objetivo
Desenvolver um modelo preditivo capaz de estimar a resistência do concreto com base em suas propriedades e composição, auxiliando profissionais da construção civil na tomada de decisões.

## 📋 Dataset
O conjunto de dados utilizado contém informações sobre diferentes composições de concreto e suas respectivas resistências à compressão.

### Características do Dataset:
- **Fonte**: UCI Machine Learning Repository
- **Amostras**: 1030 registros
- **Features**: 8 variáveis explicativas
- **Target**: Resistência à compressão

### Variáveis:
- Cimento
- Escória de alto forno
- Cinzas volantes
- Água
- Superplastificante
- Agregado graúdo
- Agregado fino
- Idade

## 🛠️ Tecnologias Utilizadas
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib

## 📈 Metodologia
1. **Preparação dos Dados**
   - Carregamento do dataset
   - Análise exploratória
   - Tratamento de dados

2. **Análise Exploratória**
   - Estatísticas descritivas
   - Visualização de correlações
   - Análise de distribuições

3. **Modelagem**
   - Divisão treino/teste
   - Padronização dos dados
   - Implementação do modelo de regressão

4. **Avaliação**
   - Métricas de performance (R², RMSE)
   - Análise dos coeficientes
   - Validação do modelo

## 📊 Resultados
- R² Score: 0.6275
- RMSE: 9.7967
- Identificação das variáveis mais influentes na resistência do concreto

## 🚀 Como Usar
1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/nome-do-repo.git
```

2. Instale as dependências
```bash
pip install -r requirements.txt
```

3. Execute o notebook Jupyter
```bash
jupyter notebook
```

## 📝 Requisitos
- Python 3.x
- Bibliotecas listadas em `requirements.txt`

## 📌 Observações
- O modelo atual utiliza regressão linear simples
- Possibilidades de melhorias incluem:
  - Implementação de outros algoritmos
  - Feature engineering
  - Otimização de hiperparâmetros

## 👥 Contribuições
Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## 📄 Licença
Este projeto está sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## ✉️ Contato
Mauricio Gomes - mauriciolxrdev@gmail.com

## 🔗 Links Úteis
- [Dataset Original](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength)
- [Documentação Scikit-learn](https://scikit-learn.org/stable/)

---
⌨️ com ❤️ por Mauricio
