# Projeto Preço de Imovéis de São Paulo

## Autor: Guilherme Iram

O projeto tem por objetivo, baseado nas características quantitativas do dataset, fazer uma análise visual desses atributos e propor um modelo de regressão.
O resultado esperado é um modelo o qual faz previsões dos preços das casas baseadando-se nas características desejadas pelo cliente.

## 1 - Carregando as bibliotecas
   
    matplotlib==3.6.0
    numpy==1.23.3
    pandas==1.5.0
    scikit-learn==1.1.2
    seaborn==0.12.0
    statistics==1.0.3.5

## 2 - Carregando o dataset, tratamento & análises prévias
    
    Etapa dedicada a diagnósticar os dados faltantes e/ou sujos e também seleção de features mais relevantes para aplicar Machine Learning. 

## 3 - Limpeza dos dados
    
    Cada um dos dados foi gravado como sendo string ou 'object',   portanto, cada uma das features selecionadas precisa de um tratamento para um formato numérico adequado.

### 3.1 - Tratando a coluna 'preco'
### 3.2 - Tratando a coluna 'area_metro_quadrado'
### 3.3 - Tratando a coluna 'quartos'
### 3.4 - Tratando a coluna 'banheiros'
### 3.5 - Tratando a coluna 'vagas'
### 3.6 - Cotemplando as mudanças & salvando novo xlsx
