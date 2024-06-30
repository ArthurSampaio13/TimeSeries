# README para Análise de Séries Temporais

Este repositório contém uma coleção de notebooks e scripts focados na análise de séries temporais utilizando diversos modelos estatísticos e de machine learning. Os principais tópicos abordados incluem ARIMA, AR, MA, I, SARIMA, SARIMAX, modelos do `sklearn`, e métodos da biblioteca `nixtla`.

## Modelos Abordados

### ARIMA
- **AR (AutoRegressive)**: Modelo autorregressivo, que utiliza as dependências entre uma observação e uma série de defasagens.
- **I (Integrated)**: Parte do modelo que diferencia a série para torná-la estacionária.
- **MA (Moving Average)**: Modelo de média móvel, que utiliza a relação entre uma observação e um erro residual de um modelo de média móvel aplicado às defasagens.

### SARIMA
- **Seasonal ARIMA**: Extensão do ARIMA que lida com dados sazonais, incluindo componentes sazonais adicionais nos termos AR, I e MA.

### SARIMAX
- **Seasonal ARIMA with Exogenous Regressors**: Variante do SARIMA que inclui variáveis externas para melhorar as previsões.

### Modelos com `sklearn`
- Implementações utilizando bibliotecas do `sklearn` para modelos de regressão e previsões com séries temporais.

### Modelos com `nixtla`
- Utilização da biblioteca `nixtla` para previsão com algoritmos avançados e otimização de hiperparâmetros.
