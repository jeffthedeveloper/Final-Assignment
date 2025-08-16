# Análise e Visualização de Dados de Ações (Stocks) 📊📈

## 📋 Descrição do Projeto

Este projeto demonstra a extração e visualização de dados financeiros, uma habilidade fundamental em ciência de dados. A partir de dados de ações da **Tesla (TSLA)** e da **GameStop (GME)**, o projeto utiliza bibliotecas como `yfinance` para obter dados históricos e `BeautifulSoup` para web scraping de dados de receita. Os dados extraídos são então processados e visualizados em gráficos interativos para facilitar a análise.

Este notebook aborda as seguintes tarefas principais:

- Extração de dados de ações usando a biblioteca `yfinance`.
- Web scraping para coletar dados de receita trimestral.
- Limpeza e processamento dos dados coletados.
- Criação de gráficos que combinam informações de preço de ações e receita.

---

## 🛠️ Ferramentas e Tecnologias

O projeto utiliza as seguintes bibliotecas Python:

- **`yfinance`**: Para extrair dados de ações.
- **`pandas`**: Para manipulação e análise de dados em DataFrames.
- **`requests`**: Para fazer requisições HTTP e baixar páginas web.
- **`BeautifulSoup`**: Para analisar o HTML e extrair informações de tabelas.
- **`plotly`**: Para criar visualizações de dados interativas.

### 📝 Instalação

Para executar este projeto, você precisa instalar as bibliotecas necessárias. O comando a seguir pode ser usado para instalar todas as dependências:

```bash
!pip install yfinance==0.1.67
!mamba install bs4==4.10.0 -y
!pip install nbformat==4.2.0
!pip install requests
!pip install pandas
!pip install plotly
```

-----

## 🚀 Estrutura do Projeto

O notebook está dividido em seções para uma melhor organização e fluxo de trabalho:

### 1\. **Definição da Função `make_graph`**

Uma função utilitária para gerar gráficos a partir de DataFrames de ações e receita.

### 2\. **Extração de Dados da Tesla (TSLA)**

  - **Questão 1**: Coleta de dados históricos de preços de ações da TSLA usando `yfinance`.
  - **Questão 2**: Web scraping da receita trimestral da TSLA de uma página web.

### 3\. **Extração de Dados da GameStop (GME)**

  - **Questão 3**: Coleta de dados históricos de preços de ações da GME usando `yfinance`.
  - **Questão 4**: Web scraping da receita trimestral da GME de uma página web.

### 4\. **Visualização dos Dados**

  - **Questão 5**: Plotagem do gráfico de ações e receita da Tesla.
  - **Questão 6**: Plotagem do gráfico de ações e receita da GameStop.

-----

## 🧑‍💻 Como Usar

Para utilizar o projeto, siga os seguintes passos:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/jeffthedeveloper/Final-Assignment
    ```
2.  **Abra o notebook:**
    Abra o arquivo `.ipynb` em um ambiente como Jupyter Notebook ou Google Colab.
3.  **Execute as células:**
    Siga a ordem das células no notebook para executar o código passo a passo. Certifique-se de que todas as dependências foram instaladas corretamente antes de começar.

-----

## ✍️ Autores

  - **Joseph Santarcangelo**: PhD em Engenharia Elétrica com foco em aprendizado de máquina, processamento de sinais e visão computacional. Atua na IBM.
  - **Azim Hirjani**

-----

