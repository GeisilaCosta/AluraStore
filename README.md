# AluraStore
🛍️ AluraStoreBR
Projeto desenvolvido como parte do Challenge de Data Science da Alura.
O objetivo é realizar uma análise exploratória dos dados de vendas de quatro lojas online, gerar visualizações, calcular métricas importantes e analisar padrões de comportamento dos clientes.

📦 Sobre o Projeto
Neste projeto, realizamos:

Análise de frete médio por loja.

Identificação da categoria de produto mais vendida.

Análises de avaliação dos clientes.

Visualização da distribuição geográfica das vendas utilizando latitude e longitude.

Geração de gráficos de dispersão e mapas de calor.

Exploração de padrões de vendas por localização.

🛠️ Tecnologias utilizadas
Python

Pandas

Seaborn

Matplotlib

Folium (opcional para mapa interativo)

Google Colab

📚 Base de Dados
Os dados foram fornecidos pela Alura e estão disponíveis em CSV:

Loja 1: loja_1.csv

Loja 2: loja_2.csv

Loja 3: loja_3.csv

Loja 4: loja_4.csv

📊 Principais Análises
📦 Frete Médio por Loja
Loja 1: R$ 34,69

Loja 2: R$ 33,62

Loja 3: R$ 33,07

Loja 4: R$ 31,27

🛒 Categoria Mais Vendida
A categoria com maior número de vendas foi identificada através da contagem de ocorrências em todas as lojas combinadas.

📍 Distribuição Geográfica
Utilizamos gráficos de dispersão e mapas de calor para visualizar onde as vendas acontecem, e observamos que:

As vendas estão concentradas em certas regiões específicas.

Algumas lojas possuem maior volume de vendas em determinadas áreas.

⭐ Avaliação dos Clientes
Avaliações analisadas para cada loja.

Distribuição das notas de 1 a 5 estrelas.

📈 Visualizações Geradas
Gráficos de dispersão (scatterplot) para localização das vendas.

Heatmaps (kdeplot) para concentração de vendas por região.

Gráficos de barras para avaliação média e quantidade de vendas por categoria.

🚀 Como Executar
Clone o repositório:

bash
Copiar
Editar
git clone (https://github.com/GeisilaCosta/AluraStore.git)
Instale as bibliotecas necessárias:

bash
Copiar
Editar
pip install pandas matplotlib seaborn folium
Execute o notebook AluraStoreBR.ipynb no Google Colab ou Jupyter Notebook.

💡 Ideias Futuras
Análise temporal das vendas (por mês ou estação do ano).

Modelos preditivos para estimar vendas futuras.

Comparação de desempenho entre lojas com técnicas de Machine Learning.
