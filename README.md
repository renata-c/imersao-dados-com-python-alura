# Dashboard de Salários na Área de Dados

Este projeto foi desenvolvido durante o evento **Imersão Dados com Python**, realizado pela [Alura](https://www.alura.com.br/).  
O objetivo foi criar um **dashboard interativo** para analisar dados salariais de profissionais da área de dados ao redor do mundo.

## 🚀 Funcionalidades

- Filtros por **Local da Empresa**, **Ano**, **Senioridade**, **Tipo de Contrato** e **Tamanho da Empresa**.
- Exibição de **KPIs** como Salário Médio, Salário Máximo, Total de Registros e Cargo mais Frequente.
- Gráficos interativos com **Plotly**:
  - Top 10 cargos por salário médio
  - Distribuição de salários
  - Proporção de tipos de trabalho (remoto, híbrido, presencial)
  - Mapa com salário médio de Cientistas de Dados por país
- Tabela detalhada com todos os dados filtrados.

## 🛠 Tecnologias Utilizadas

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Plotly](https://plotly.com/python/)
- [Streamlit](https://streamlit.io/)

## 📂 Estrutura do Projeto
  📦 imersao-dados-com-python-alura
 ┣ 📜 app.py                 # Código principal do Streamlit
 ┣ 📜 dados-tratados.csv     # Base de dados tratada
 ┣ 📜 analise-tratamento-dados.ipynb  # Notebook com exploração e tratamento
 ┣ 📜 requirements.txt       # Dependências do projeto
 ┗ 📜 README.md              # Documentação


## 🌐 Dashboard Online
Você pode acessar a versão online do dashboard no Streamlit Cloud:
🔗 [Acesse aqui](https://imersao-dados-com-python-alura-renata-c.streamlit.app/)

## 💻 Como rodar localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/renata-c/imersao-dados-com-python-alura.git

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   
3. Rode o projeto
   ```bash
   streamlit run app.py
