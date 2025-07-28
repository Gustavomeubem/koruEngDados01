📊 Análise de Dados de Vendas - Projeto de Engenharia de Dados
https://img.shields.io/badge/Python-3.8%252B-blue
https://img.shields.io/badge/Pandas-1.3.0%252B-orange
https://img.shields.io/badge/license-MIT-green

Este projeto realiza uma análise exploratória de dados (EDA) de um conjunto de dados de vendas, fornecendo insights valiosos sobre desempenho de vendas, comportamento do cliente e tendências de mercado.

📂 Estrutura do Projeto
text
sales-data-analysis/
├── data/
│   └── sales_data_sample.csv       # Dataset original
├── notebooks/
│   └── sales_analysis.ipynb        # Jupyter Notebook com a análise
├── scripts/
│   └── sales_analysis.py           # Script Python para análise
├── README.md                       # Este arquivo
└── requirements.txt                # Dependências do projeto
🚀 Como Executar
Clone o repositório

bash
git clone https://github.com/seu-usuario/sales-data-analysis.git
cd sales-data-analysis
Configure o ambiente virtual (opcional)

bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
Instale as dependências

bash
pip install -r requirements.txt
Execute a análise

bash
python scripts/sales_analysis.py
Ou abra o Jupyter Notebook:

bash
jupyter notebook notebooks/sales_analysis.ipynb
🔍 Principais Análises Realizadas
📈 Tendências de vendas ao longo do tempo

🌍 Distribuição geográfica das vendas

🏷️ Desempenho por linha de produtos

📦 Status e distribuição de pedidos

💰 Análise de tamanho de negócios (DEALSIZE)

📊 Insights Iniciais
Produtos mais vendidos: Classic Cars e Motorcycles dominam as vendas

Mercados-chave: EUA, França e Espanha são os principais países

Sazonalidade: Q4 apresenta maior volume de vendas

Status: 85% dos pedidos estão como "Shipped"

🤝 Como Contribuir
Contribuições são bem-vindas! Siga estes passos:

Faça um fork do projeto

Crie sua branch (git checkout -b feature/AmazingFeature)

Commit suas mudanças (git commit -m 'Add some AmazingFeature')

Push para a branch (git push origin feature/AmazingFeature)

Abra um Pull Request
