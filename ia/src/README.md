# IA/Machine Learning - Iris K-Means Clustering

## 📝 Descrição

Módulo responsável pela análise de clustering K-Means aplicada ao dataset Iris. Este projeto demonstra como algoritmos não supervisionados podem identificar grupos naturais nos dados, comparando os clusters encontrados com as espécies reais das flores.

## 🚀 Funcionalidades

- Carregamento do dataset Iris do scikit-learn
- Análise e exploração das características das flores (comprimento/largura de sépalas e pétalas)
- Pré-processamento com StandardScaler para normalização dos dados
- Aplicação do algoritmo K-Means com 3 clusters
- Redução de dimensionalidade com PCA para visualização em 2D
- Comparação visual entre clusters K-Means e espécies reais
- Visualização dos centróides dos clusters

## 🛠️ Tecnologias Utilizadas

### Core ML

- **Scikit-learn** - Algoritmos de clustering (K-Means), redução de dimensionalidade (PCA) e pré-processamento (StandardScaler)

### Processamento de Dados

- **Pandas** - Manipulação e estruturação dos dados do Iris dataset

### Visualização

- **Matplotlib** - Visualizações dos clusters e comparação com espécies reais

## 📦 Instalação

As dependências são gerenciadas pelo arquivo raiz do projeto. Certifique-se de ter o ambiente virtual ativo:

```bash
# Se usando Pipenv
pipenv shell

# Se usando venv
source venv/bin/activate  # Linux/Mac
# ou
venv\Scripts\activate     # Windows
```

## 📋 Estrutura Atual

```text
ia/src/
├── notebooks/
│   └── project.ipynb          # Análise completa K-Means do dataset Iris
└── README.md                  # Este arquivo
```

## 📊 Notebook Disponível

- `project.ipynb` - Análise completa de clustering K-Means aplicada ao dataset Iris, incluindo:
  - Carregamento e exploração dos dados
  - Pré-processamento com StandardScaler
  - Aplicação do algoritmo K-Means
  - Visualização dos resultados com PCA
  - Comparação entre clusters encontrados e espécies reais

## 🔬 Pipeline Implementado

1. **Carregamento de Dados**
   - Importação do dataset Iris via scikit-learn
   - Estruturação em DataFrame pandas

2. **Pré-processamento**
   - Normalização com StandardScaler
   - Preparação dos dados para clustering

3. **Clustering**
   - Aplicação do K-Means com 3 clusters
   - Definição de centróides dos clusters

4. **Redução de Dimensionalidade**
   - Aplicação do PCA para visualização em 2D
   - Preservação da variância explicada

5. **Visualização e Análise**
   - Gráficos comparativos dos clusters vs espécies reais
   - Análise da eficácia do clustering não supervisionado
