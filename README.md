# 📊 Dashboard de Salários na Área de Dados

Aplicação interativa desenvolvida com **Streamlit** e **Plotly** para explorar dados salariais na área de dados.  
Permite filtrar informações por ano, senioridade, tipo de contrato e tamanho da empresa, exibindo métricas principais, gráficos e uma tabela detalhada.

## ✨ Funcionalidades
- Filtros dinâmicos para personalizar a análise.
- Gráficos interativos em Plotly.
- KPIs automáticos: salário médio, salário máximo, total de registros e cargo mais frequente.
- Visualização geográfica dos salários de Cientistas de Dados.
- Distribuição salarial por faixa.
- Tabela detalhada dos dados filtrados.

## 🖼️ Demonstração
<img width="3309" height="2339" alt="Dashboard de Salários na Área de Dados" src="https://github.com/user-attachments/assets/f4c1acdd-a2b5-480d-a7ec-defcd9022a9e" />

## 📂 Estrutura do Projeto
```
├── app.py                    # Código principal da aplicação Streamlit
├── dados-imersao-final.csv   # Dataset utilizado no dashboard
├── requirements.txt          # Lista de dependências para instalar com pip
├── README.md                 # Documentação do projeto
└── LICENSE                   # Arquivo de licença do projeto
```

Os dados utilizados foram obtidos a partir do dataset disponível em:
[GitHub - vqrca/dashboard_salarios_dados](https://github.com/vqrca/dashboard_salarios_dados)

## 🛠 Tecnologias utilizadas
- Python 3.10+
- Streamlit
- Pandas
- Plotly Express

## 🚀 Como executar localmente
1. **Clone este repositório**
```
git clone https://github.com/seu-usuario/nome-do-repo.git
cd nome-do-repo
```

2. **Crie um ambiente virtual e instale as dependências**
```
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
pip install -r requirements.txt
```

3. **Execute o aplicativo**
```
streamlit run app.py
```

4. **Abra no navegador**
```
http://localhost:8501
```

## 📜 Licença
Este projeto está licenciado sob a MIT License.
