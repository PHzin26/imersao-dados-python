# 🎲 Dashboard de Análise de Salários na Área de Dados

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-239120?logo=plotly&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)

Este projeto é um **Dashboard Interativo** desenvolvido em Python para explorar, analisar e visualizar dados salariais de profissionais da área de dados ao redor do mundo. 

O projeto foi desenvolvido como parte da imersão/curso de Análise de Dados em Python oferecido pela **Alura**.

---

## 🚀 Funcionalidades

O dashboard oferece uma interface amigável e interativa, permitindo aos usuários extrair *insights* valiosos através de diversas ferramentas:

* **Filtros Dinâmicos (Barra Lateral):** Refine a análise cruzando dados por:
    * Ano da pesquisa
    * Nível de Senioridade
    * Tipo de Contrato
    * Tamanho da Empresa
* **Métricas Gerais (KPIs):** Visualização rápida e direta do Salário Médio, Salário Máximo, Total de Registros e o Cargo mais frequente, atualizados em tempo real conforme os filtros.
* **Visualizações Gráficas Interativas:** Gráficos gerados com a biblioteca Plotly:
    * 📊 **Top 10 Cargos:** Gráfico de barras horizontais mostrando as profissões com os maiores salários médios.
    * 📈 **Distribuição de Salários:** Histograma interativo para entender como os salários estão distribuídos e onde estão as maiores concentrações.
    * 🍩 **Proporção de Tipos de Trabalho:** Gráfico de rosca detalhando a adoção do modelo remoto, presencial ou híbrido.
    * 🗺️ **Mapa Global de Salários:** Mapa coroplético mundial destacando a média salarial para Cientistas de Dados (`Data Scientist`) por país.
* **Exploração de Dados Brutos:** Tabela interativa no final da página para consultar os dados linha a linha com base nos filtros aplicados.

---

## 🛠️ Tecnologias Utilizadas

* **[Python](https://www.python.org/):** Linguagem principal do projeto.
* **[Streamlit](https://streamlit.io/):** Framework para a criação rápida da interface web interativa.
* **[Pandas](https://pandas.pydata.org/):** Biblioteca para manipulação e análise de dados tabulares.
* **[Plotly Express](https://plotly.com/python/):** Biblioteca para a criação de gráficos interativos e responsivos.

---

## ⚙️ Como executar o projeto localmente

Siga os passos abaixo para rodar o dashboard na sua própria máquina:

**1. Clone o repositório:**
```bash
git clone https://github.com/PHzin26/imers-o-dados-python.git
cd imers-o-dados-python

2. Instale as dependências:
Certifique-se de ter o Python instalado. É recomendado o uso de um ambiente virtual (venv).

pip install pandas streamlit plotly

3. Execute a aplicação Streamlit:

streamlit run app.py

(Nota: substitua app.py pelo nome do arquivo principal do seu código Python, caso seja diferente).

4. Acesse no navegador:
O Streamlit abrirá automaticamente no seu navegador padrão. Caso não abra, acesse http://localhost:8501.

💡 Sobre os Dados
Os dados utilizados neste projeto são consumidos diretamente de um repositório remoto no formato .csv e contêm informações globais anonimizadas sobre profissionais de dados, incluindo cargos, localidade, tipo de contrato e compensação financeira em Dólares Americanos (USD).

👨‍💻 Autor
Feito por Pedro Henrique durante o curso da Alura.
Sinta-se à vontade para contribuir, abrir issues ou entrar em contato!

