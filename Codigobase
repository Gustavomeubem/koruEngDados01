import pandas as pd

# Carregar os dados
df = pd.read_csv('sales_data_sample.csv')

# Análise das 2 primeiras linhas
print("Primeiras 2 linhas do dataset:")
print(df.head(2))

# Informações básicas sobre o dataset
print("\nInformações do dataset:")
print(df.info())

# Estatísticas descritivas
print("\nEstatísticas descritivas:")
print(df.describe())

# Análise de produtos mais vendidos
print("\nTop 5 produtos por quantidade vendida:")
print(df.groupby('PRODUCTLINE')['QUANTITYORDERED'].sum().sort_values(ascending=False).head(5))

# Análise de vendas por país
print("\nTop 5 países por volume de vendas:")
print(df.groupby('COUNTRY')['SALES'].sum().sort_values(ascending=False).head(5))

# Análise de status dos pedidos
print("\nDistribuição de status dos pedidos:")
print(df['STATUS'].value_counts())

# Análise sazonal
print("\nVendas por trimestre:")
print(df.groupby('QTR_ID')['SALES'].sum())
