📌 Contexto de Negócio
O objetivo principal foi responder a perguntas críticas para a satisfação do cliente e saúde financeira da operação:

Onde está o gargalo? Identificar se a demora ocorre na postagem (vendedor) ou no transporte (logística).

Variabilidade Regional: Analisar como o estado de destino influencia a previsibilidade da entrega.

Gestão de Expectativas: Comparar o prazo estimado vs. o prazo real para otimizar a conversão no checkout.

🛠️ Tecnologias Utilizadas
Python 3.13

Pandas: Manipulação e limpeza de grandes volumes de dados

Matplotlib & Seaborn: Visualização de dados estatísticos (Histogramas e Boxplots)

Jupyter Notebook: Ambiente de desenvolvimento e documentação

📊 Principais Insights
A Falácia da Média: A análise de distribuição revelou que, embora a maioria dos pedidos chegue antes do prazo, a "cauda longa" de atrasos em regiões específicas gera riscos operacionais altos.

Desigualdade Logística: Através de Boxplots, foi possível visualizar que estados do Norte e Nordeste possuem uma variabilidade de entrega muito superior ao Sudeste, exigindo estratégias de frete diferenciadas.

Otimização de Postagem: Identificamos que uma parcela significativa do atraso ocorre antes da coleta, na etapa de processamento do vendedor.

📁 Estrutura do Repositório
projeto.ipynb: Notebook com todo o código de ETL, limpeza e visualização.
