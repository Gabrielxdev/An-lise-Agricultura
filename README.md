# Análise de Preços e Variações de Produtos Agrícolas

## 📊 Objetivo
Este projeto realiza uma análise exploratória de dados sobre preços e variações percentuais de matérias-primas agrícolas ao longo do tempo, utilizando Python e bibliotecas como Pandas, Matplotlib e Seaborn.

## 🛠️ Principais Etapas da Análise

### 1. Importação e Configuração Inicial
- Carregamento das bibliotecas essenciais (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`)
- Configuração do estilo visual dos gráficos com `Seaborn`

### 2. Carregamento e Inspeção dos Dados
- Leitura do arquivo CSV `agricultural_raw_material.csv` usando `pd.read_csv()`
- Visualização inicial dos dados com `.head()`
- Verificação de tipos de dados com `.info()`
- Detecção e tratamento de valores nulos

### 3. Limpeza e Pré-processamento
- Remoção de caracteres especiais (% e vírgulas) dos valores percentuais
- Conversão de tipos de dados para `float`
- Transformação da coluna 'Month' para formato `datetime` e definição como índice
- Renomeação das colunas para português para melhor compreensão

### 4. Análise Exploratória
- Dados mensais de preços e variações percentuais para produtos como:
  - Lã grossa e lã fina
  - Algodão
  - Borracha  
  - Madeira
  - Celulose
- Período analisado: 1992 a 2016 (dados iniciais)
- Tratamento de valores ausentes
- Conversão de tipos de dados para análises quantitativas

## 📈 Próximos Passos
-  Criação de visualizações temporais para tendências
-  Análise de correlação entre commodities
-  Identificação de padrões sazonais
-  Comparação entre variações percentuais

## 🛠️ Tecnologias Utilizadas
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
