# ClearBank - Análise Financeira com Python 📊

Este projeto consiste em um pipeline de dados desenvolvido em Python para a fintech fictícia **ClearBank**. O objetivo principal é ler um arquivo de transações mensais em formato CSV, realizar a limpeza e validação dos dados, computar métricas financeiras cruciais e exportar um relatório consolidado em JSON, além de alertar sobre possíveis transações suspeitas.

Projeto desenvolvido como desafio prático para o módulo de fundamentos de Python aplicados à análise de dados da Pós-Graduação.

## 🚀 Tecnologias Utilizadas

* **Python 3.10+**
* **Módulos Nativos:** `csv`, `json`, `datetime`
* **Google Colab / Jupyter Notebook** (.ipynb)

## 📁 Estrutura do Repositório

* `desafio-final.ipynb`: Notebook contendo todo o código estruturado em funções e as saídas da execução.
* `transacoes.csv`: Arquivo de entrada com os dados brutos simulados (incluindo registros válidos e inválidos).
* `relatorio.json`: Arquivo gerado automaticamente pelo script com o resumo métrico mensal estruturado.

## 🔧 Como Executar o Projeto

Você pode executar este projeto de duas formas:

### Opção 1: Google Colab (Recomendado)
1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Vá em `Arquivo` -> `Upload de notebook` e selecione o arquivo `desafio-final.ipynb` deste repositório.
3. Na barra lateral esquerda do Colab, clique no ícone da pasta e faça o upload do arquivo `transacoes.csv`.
4. Vá no menu superior, clique em `Ambiente de execução` -> `Executar tudo`.

### Opção 2: Ambiente Local
1. Certifique-se de ter o Python 3.10 ou superior instalado.
2. Instale o Jupyter Notebook (`pip install notebook`) se preferir a interface visual.
3. Coloque os arquivos `desafio-final.ipynb` e `transacoes.csv` na mesma pasta.
4. Execute o notebook.

## 📋 O que o Notebook gera como saída
* **No Terminal:** Um resumo detalhado da limpeza de dados (linhas válidas vs inválidas), métricas mensais (faturamento de crédito, débito, saldo, ticket médio, maior e menor transação) e um bloco dedicado a alertas de movimentações suspeitas acima de R$ 10.000,00.
* **Arquivo Físico:** O arquivo `relatorio.json` populado dinamicamente com a data da execução.
