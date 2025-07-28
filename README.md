# # 📊 Superstore Dataset – Análise Exploratória
## introdução:
Este projeto realiza uma **análise exploratória de dados (EDA)** sobre vendas e lucros de uma rede de supermercados fictícia.  
O objetivo é identificar **produtos, regiões e categorias mais lucrativas**, além de oportunidades de otimização de vendas(ainda em desenvolvimento).

a base de dados esta disponivel no Kaggle: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final</br>

## 🛠 Tecnologias Utilizadas
- Python (Pandas, Numpy, Seaborn, Matplotlib)
- Jupyter Notebook
- GitHub para versionamento

## 📈 Principais Insights

✅ **Tecnologia** é a categoria mais lucrativa  
✅ **Móveis** têm vendas altas, mas margens muito baixas  
✅ **Telefones e Cadeiras** são os produtos mais vendidos  
✅ **Nova York e Los Angeles** lideram em vendas entre as cidades  
✅ **Califórnia** é o estado com maior volume de vendas

## Analise dos Gráficos:
### 1 - TOP 10 produtos mais vendidos:
![Grafico do top 10 mais vendidos](image/top10.png)
O gráfico acima apresenta os 10 produtos mais vendidos na empresa. estranhamente, o produto mais vendido apresenta um valor de venda muito alto em relação aos outros. 
esse alto valor de vendas pode ser explicado pelos seguinte fatores:
  - Alta demanda e utilidade recorrente;
  - Campanhas promocionais e marketing direcionado;
  - Disponibilidade em estoque e logística eficiente;
  -  Reputação e confiabilidade do produto;
  -  Falta de variedade entre os produtos secundários;

a loja em analise, apresenta 3 categorias sendo, tecnologia, suprimentos e moveis. de acordo com o gráfico os produtos mais vendidos são de categoria suprimento seguindo de tecnologia e por ultimo moveis.
pela analise de vendas, podemos impor que empresas são as maiores clientes desse super mercado.

### 2 - total de vendas e lucro:
![Grafico do total de vendas e lucro](image/total_Lucro.png)
no Grafico acima, demonstra que as 3 categorias de produtos são bastante proximos em vendas, com tecnologia com apenas 3 a 4% maior em relação as duas categorias. o segundo grafico demonstra que a maior lucratividade esta vindo tambem da categoria de tecnologia, sinal que esse é o setor mais rentavel. interessante perceber que a categoria de móveis ainda sendo maior em vendas que a de suprimentos, ele apresenta uma lucratividade extremamente baixa, o que pode ser um motivo de preocupação. talvez pelos motivos abaixo:
  - Os custos de aquisição/produção são muito altos
  - O preço de venda é muito baixo
  - Há muitos descontos aplicados
  - Existem muitos custos com logística ou devoluções

### 3 - TOP 10 de vendas por sub categorias
![Grafico do top 10 de vendas por sub categorias](image/top10_vendas.png)
analisando o grafico acima, notamos que a venda de telefones e cadeiras são bem proximas e tambem com um destaque em relação aos outros produtos. porem, a baixa lucratividade da categoria de móveis demonstra que tem algo extremamente problematico com a venda dessa categoria, no grafico acima, o segundo maior em vendas pertence aos moveis e ainda há 3 produtos nessa lista, apresentando 2 produtos a mais em relação a categoria de suprimentos.</br>

### 4 - vendas por localidade:
![Grafico de vendas por localidades](image/total_vendas.png)
analisando o gráfico de cidades, nova York e los angeles lideram nas vendas, é interessante perceber que nova York ainda apresenta quase 100k de vendas a mais que los angeles, demonstrando que essa cidade esta sendo a mais lucrativa. analisando o gráfico sobre os estados, a california lidera o ranking com mais de 100k de vendas em relação ao estado de nova York que esta em segundo em vendas.</br>
analisando o gráfico de cidades, há tres cidades do estado de california no top 10 de vendas sendo los angeles, san Francisco e san diego, isso explica o alto volume de vendas estadual, porem, e possível as outras cidades que estão fora da lista tenham uma lucratividade extremamente baixa. já o estado de nova York lidera na segunda posição, com mais de 100k de vendas em relação aos outros estados. isso demonstra o quanto a cidade de nova York e lucrativa para essa empresa.

## ✅ Conclusões e Recomendações

📌 A categoria **Tecnologia** é a mais rentável e deve receber mais investimento.  
📌 A categoria **Móveis** precisa de revisão de preços e custos logísticos.  
📌 As cidades **Nova York e Los Angeles** são estratégicas para vendas.  
