### 📊 Análise de Dados - Alura Store

Este projeto foi desenvolvido como parte de um estudo de Análise de Dados com o objetivo de auxiliar o Senhor João, proprietário da rede fictícia Alura Store, a decidir qual das quatro lojas vender.
Utilizando ferramentas de Data Science como Python, Pandas, Matplotlib, Seaborn e Folium, foram realizadas análises detalhadas sobre os dados de desempenho das lojas.

##🔍 Objetivos e Métricas Avaliadas

As seguintes análises foram realizadas:
💰 Faturamento total por loja
📦 Vendas por categoria de produtos
🌟 Média das avaliações dos clientes
📉 Produtos mais e menos vendidos
🚚 Frete médio por loja
🗺️ Análise geográfica das vendas (desafio extra)

##Com base nos resultados, foi elaborada uma recomendação final justificada por dados e visualizações.

##📁 Estrutura do Projeto
O repositório contém os seguintes arquivos:
analise_lojas.ipynb – Notebook Jupyter com todo o código e análises.
mapa_interativo.html – Mapa interativo gerado com Folium.
dados.csv (opcional) – Conjunto de dados utilizado nas análises.
requirements.txt – Lista de dependências necessárias.

##🛠️ Pré-requisitos
Para rodar este projeto localmente, você precisará de:
Python 3.x
Bibliotecas Python:
pandas
matplotlib
seaborn
folium
Git (opcional, para clonar o repositório)

##Instale as dependências com:
bash
Copiar
Editar
pip install -r requirements.txt

💡 Dica: Se estiver usando o Google Colab, você pode instalar as bibliotecas diretamente no notebook.

##▶️ Como Executar o Projeto
1. Clone o repositório
bash
Copiar
Editar
git clone https://github.com/seu-usuario/nome-do-repositorio.git
2. Instale as dependências
bash
Copiar
Editar
cd nome-do-repositorio
pip install -r requirements.txt
3. Execute o notebook
Abra o arquivo analise_lojas.ipynb em um ambiente Jupyter ou no Google Colab, garantindo que o arquivo dados.csv esteja na mesma pasta.

###📊 Análises Realizadas
1. Faturamento Total por Loja
Identificamos a loja com menor desempenho financeiro. Resultado exibido em gráfico de barras.
2. Vendas por Categoria de Produtos
Visualização das categorias mais e menos vendidas em cada loja, com gráficos comparativos.
3. Média das Avaliações dos Clientes
Análise do nível de satisfação dos clientes por loja.
4. Produtos Mais e Menos Vendidos
Identificação dos produtos com maior e menor volume de vendas.
5. Frete Médio por Loja
Comparação dos custos logísticos entre as lojas.
6. Análise Geográfica (Desafio Extra)
Geração de um mapa interativo com base nas colunas de latitude e longitude, disponível em mapa_interativo.html.

###✅ Recomendação Final
Recomenda-se a venda da Loja 4, devido a:
Faturamento mais baixo
Baixa diversidade de produtos vendidos
Avaliações de clientes abaixo da média
Custos de frete elevados
Localização geográfica desfavorável
Essa decisão permitirá ao Senhor João focar nas lojas mais lucrativas e com melhor desempenho.

##🐞 Problemas Conhecidos
Dados incompletos: Valores ausentes foram tratados com substituições ou remoções.
Visualização do mapa: O GitHub não renderiza arquivos .html diretamente. Para visualizar o mapa, hospede-o no GitHub Pages ou utilize outro serviço de hospedagem.

##🤝 Contribuições
Contribuições são bem-vindas! Para colaborar:
Faça um fork do repositório.

Crie uma nova branch:
bash
Copiar
Editar
git checkout -b feature/nova-analise
Faça o push das alterações:

bash
Copiar
Editar
git push origin feature/nova-analise
Abra um Pull Request explicando suas modificações.

##📄 Licença
Este projeto está licenciado sob a MIT License. Sinta-se à vontade para usar, modificar e distribuir conforme necessário.

