# Brasileirão Série A - Player Stats

Este projeto realiza o web scraping de dados dos jogos do Campeonato Brasileiro de Futebol - Série A. O objetivo é extrair informações como data, horário, estádio, times e resultado de partidas para posterior análise.

## 📋 Descrição

O script de web scraping foi desenvolvido em Python utilizando bibliotecas como `BeautifulSoup` e `requests`. A ideia principal é acessar páginas da web com informações sobre os jogos e coletar os dados automaticamente.

Os dados extraídos podem ser usados para diversas finalidades, como:

- Análises estatísticas dos times;
- Previsões de resultados;
- Geração de insights sobre a performance dos clubes ao longo da temporada.

## 🛠️ Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas**:
  - `requests`: Para realizar requisições HTTP e obter o conteúdo das páginas.
  - `BeautifulSoup`: Para fazer o parsing do HTML e facilitar a extração dos dados.
  - `pandas`: Para organizar e manipular os dados coletados.

## 📦 Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/eduardopfbp/Brasileirao-PlayerStats
    ```

2. Crie um ambiente virtual e instale as dependências:

    ```bash
    python -m venv venv
    source venv/bin/activate # Linux ou MacOS
    venv\Scripts\activate # Windows
    pip install -r requirements.txt
    ```

## 🚀 Como Executar

1. Certifique-se de que as dependências estão instaladas.
2. Execute o script principal para coletar os dados:
3. Os dados extraídos serão salvos em um arquivo `.csv` para análises futuras.

## 🗂 Estrutura do Projeto

```bash
brasileirao-serie-a-webscraping/
│
├── database.csv         # Database principal (.csv)
├── database_temp.csv    # Databse temporário (.csv)
├── links.csv            # Database com link dos jogos (.csv)
├── analises             # Jupyter Notebooks para análises exploratórias
├── main.py              # Script principal de web scraping
├── extrator_link.ipynb  # Extrator do link
├── requirements.txt     # Arquivo de dependências do Python
└── README.md            # Documentação do projeto
