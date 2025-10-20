# Iris K-Means Clustering Analysis 🌸

Projeto de análise de clustering utilizando o algoritmo K-Means aplicado ao famoso dataset Iris. O objetivo é demonstrar como o algoritmo de clustering não supervisionado pode identificar grupos naturais nos dados das espécies de flores Iris.

## 📋 Pré-requisitos

- Python 3.12 ou superior
- Git
- Pipenv ou venv (para gerenciamento de dependências)

## ✨ Tecnologias Utilizadas

- **Python 3.12** - Linguagem principal
- **Pandas** - Manipulação de dados
- **Scikit-learn** - Algoritmos de Machine Learning (K-Means, PCA, StandardScaler)
- **Matplotlib** - Visualização de dados
- **Ruff** - Linting e formatação

## 🔧 Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/Rhogger/iris-kmeans-test.git
cd iris-kmeans-test
```

### 2. Configure o ambiente virtual

Escolha uma das opções abaixo:

#### Opção A: Usando Pipenv (Recomendado)

```bash
# Instale o Pipenv (se não tiver instalado)
pip install pipenv

# Instale as dependências
pipenv install

# Ative o ambiente virtual
pipenv shell
```

#### Opção B: Usando venv

```bash
# Crie o ambiente virtual
python -m venv venv

# Ative o ambiente virtual
# Linux/Mac:
source venv/bin/activate
# Windows:
# venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt
```

## 📁 Estrutura do Projeto

```text
iris-kmeans-test/
├── ia/                    # Modelos de IA e notebooks
│   ├── src/              # Código fonte da IA
│   │   ├── notebooks/    # Notebooks de análise
│   │   │   └── project.ipynb  # Análise K-Means do Iris
│   │   └── README.md     # Documentação da IA
│   └── README.md         # Documentação da IA
├── .vscode/              # Configurações do VS Code
├── .gitattributes        # Configuração para diffs do Git
├── .gitignore            # Arquivos ignorados pelo Git
├── Pipfile               # Dependências do projeto
├── Pipfile.lock          # Lock das dependências
├── requirements.txt      # Dependências (alternativa ao Pipfile)
├── ruff.toml            # Configuração do Ruff
├── DEV.md               # Documentação de desenvolvimento
└── README.md            # Este arquivo
```

## 👨‍💻 Desenvolvimento

Instruções para desenvolvimento estão [aqui](./DEV.md)

## 📚 Documentação Adicional

- [IA README](./ia/src/README.md) - Documentação dos modelos e análises do projeto Iris K-Means

## 🎯 Objetivo do Projeto

Este projeto demonstra a aplicação prática do algoritmo K-Means para clustering não supervisionado usando o dataset Iris. O notebook inclui:

- **Carregamento e exploração** do dataset Iris
- **Pré-processamento** dos dados com StandardScaler
- **Aplicação do K-Means** com 3 clusters
- **Redução de dimensionalidade** com PCA para visualização
- **Comparação visual** entre clusters encontrados e espécies reais

## 📊 Resultados

O algoritmo K-Means consegue identificar grupos que correspondem aproximadamente às três espécies de Iris (setosa, versicolor, virginica), demonstrando a eficácia do clustering não supervisionado para descoberta de padrões naturais nos dados.

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---
