# Projeto Preço de Imovéis de São Paulo

## Autor: Guilherme Iram

O projeto tem por objetivo, baseado nas características quantitativas do dataset, fazer uma análise visual desses atributos e propor um modelo de regressão.
O resultado esperado é um modelo o qual faz previsões dos preços das casas baseadando-se nas características desejadas pelo cliente.

## Sumário do projeto

## 1 - Carregando as bibliotecas
   
    matplotlib==3.6.0
    numpy==1.23.3
    pandas==1.5.0
    scikit-learn==1.1.2
    seaborn==0.12.0
    statistics==1.0.3.5

## 2 - Carregando o dataset, tratamento & análises prévias
    
    Etapa dedicada a diagnósticar os dados faltantes e/ou sujos 
    e também seleção de features mais relevantes para aplicar 
    Machine Learning. 

## 3 - Limpeza dos dados
    
    Cada um dos dados foi gravado como sendo string ou 'object',
    portanto, cada uma das features selecionadas precisa de um 
    tratamento para um formato numérico adequado.

### 3.1 - Tratando a coluna 'preco'
### 3.2 - Tratando a coluna 'area_metro_quadrado'
### 3.3 - Tratando a coluna 'quartos'
### 3.4 - Tratando a coluna 'banheiros'
### 3.5 - Tratando a coluna 'vagas'
### 3.6 - Cotemplando as mudanças & salvando novo xlsx

## 4 - Visualização dos dados selecionados
    
    Nessa etapa, os dados serão plotados para se extrair informações
    valiosas a respeito de seus comportamentos e variações.
    Essa etapa também será fundamental para identificar elementos
    e medidas necessárias para que a aplicação de Machine Learning
    tenha resultados satisfatórios.
    
### 4.1 - Histograma do valor dos imóveis
### 4.2 - Boxplots das features dos imóveis
### 4.3 - Gráfico de dispersão da área (m²) e o custo dos imóveis (R$)

## 5 - Produzindo o modelo de Regressão
    
    Após tratar, vizualizar e selecionar os dados, chegou o momento
    de usá-los para criar um bom modelo de Machine Learning. Nesse 
    sentido, vários modelos foram testados usando diferentes métricas 
    e técnicas para avaliar o desempenho de cada estratégia de regressão
    (no presente trabalho foram usadas regressão linear, polinomial,
    árvore de decisão e floresta aleatória) tais como validação cruzada
    e métricas como R², MSE e MSA.
    

### 5.1 - Analisando a matriz de correlação
### 5.2 - Analisando o histograma da variável de controle
### 5.3 - Separação entre dados de treino e dados de teste
### 5.4 - Criando os modelos de Regressão
#### a) Dummy Regressor
#### b) Regressão Linear/ Polinomial
#### c) Decision Tree Regressor: Árvore de Decisao
#### d) Random Forest Regressor: Floresta Aleatória