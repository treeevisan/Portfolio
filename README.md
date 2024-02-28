# Bem-vindo(a) ao meu Portfólio de Análise e Ciência de Dados!
[![author](https://img.shields.io/badge/Author-Renan%20Trevisan-brightgreen)](https://www.linkedin.com/in/renantrevisan/) ![version](https://img.shields.io/badge/enthusiast-alpha_version%200.11-%23F12525)


<p align="center">
  <img src="https://github.com/treeevisan/Portfolio/assets/152438468/af11c1aa-af7b-42be-b20e-616a8a2c5cfb" width=50%>
</p>

<p align="center">
  <a href ="mailto:renan_treviz09@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=red" target="_blank"></a>
  <a href="https://www.linkedin.com/in/renantrevisan" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
</p>

## **PROJETOS**

## **Power BI**

### **Análise de Vendas - Varejista**
 - **Dashboard sobre uma varejista**, em que foram realizadas avaliações financeiras por período, produto e local. Há uma sessão de indicadores por marca e produto e uma sessão de devoluções
 - Os dados foram disponibilizados pela Hashtag e são dados ficticios
 - [Acesse o Dashboard](https://app.powerbi.com/view?r=eyJrIjoiY2RiODU2YjctMzFkOS00NjFhLWEwYTUtZDlhOTFlYWM0OWM0IiwidCI6ImMzN2IzN2EzLWU5ZTItNDJmOS1iYzY3LTRiOWI3MzhlMWRmMCJ9&pageName=ReportSection702c56a82276586d648b)
<p align="center">
  <img alt="BA" width="65%" src="https://github.com/treeevisan/Portfolio/assets/152438468/bb97d482-12f4-44de-8d7a-e882a2fa7d02">
</p>

### **Formula 1 World Championship**
- **Quem é o melhor Piloto de Formula 1 de todos os tempos?** Cada um tem o seu preferido, mas com esse estudo você pode avaliar as metricas dos seus pilotos favoritos e adquirir mais conhecimento sobre eles.
- É possível avaliar o desempenho de países, pilotos e construtores em diferentes épocas e compará-los entre si.
- Para esse projeto foi feita uma EDA (análise exploratória dos dados) com Python para entender o que cada tabela representa e como estão apresentados os dados. Além disso, foi feito o tratamento dos dados e os arquivos .xlsx foram gerados.
- [Acesse o Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGQ0MGM1OTgtOTczOS00YWY2LThiZjktYzYxODRmNjc4NjUwIiwidCI6ImMzN2IzN2EzLWU5ZTItNDJmOS1iYzY3LTRiOWI3MzhlMWRmMCJ9&pageName=ReportSectionc7917cd49305702b0e00)
<p align="center">
  <img alt="F1 WC Home" width="65%" src="https://github.com/treeevisan/Portfolio/assets/152438468/df6c3c6e-14ff-4794-8b42-c044e3690617">
</p>

## **Python**

### **Brazil Highway Traffic Accidents**
 - **ETL e data visualization**, onde foi feito o tratamento dos dados para a apresentação das informações em gráficos.
 - Nos gráficos abaixo foi feito o estudo da média de acidentes no ano versus a média de acidentes no feriado do carnaval.
 - [Acesse o projeto completo](https://www.kaggle.com/code/renantrevisan/br-hway-accidents)

<p align="center">
  <img alt="Scatter" width="47%" src="https://github.com/treeevisan/Portfolio/assets/152438468/f7772adf-516c-45f3-add5-454d9bd5be87">
  <img alt="Percent diff" width="47%" src="https://github.com/treeevisan/Portfolio/assets/152438468/f54b0e35-4fb8-4921-9b92-81c146383bea">
</p>


### **ETL Formula 1 Dataset**
ETL, do ingles, "Extração, Transformação e Carregamento" é uma parte fundamental para qualquer ação no mundo dos dados. A inspiração para esse projeto se deu quando notei que diversos notebooks que utilizaram esse dataset fizeram uma leitura manual dos dados. 
- Nesse notebook fiz a leitura e armazenamento dos dados em 1 bloco de código, nos outros são feitos os processos de tratamento dos dados. Como adendo, criei exercicios e um desafio para encorajar os iniciantes em programação a explorarem o dataset. Eles podem compreender a lógica aplicada para ler e armazenar os dados e utilizarem em outros projetos.

<p align="center">
  <img alt="Code" width="70%" src="https://github.com/treeevisan/Portfolio/assets/152438468/60f3aa35-683a-459c-abce-79d8330a3a06">
  
</p>


## **SQL**
Muitas vezes precisamos ter insights rápidos do negócio enquanto estamos fazendo uma análise. A linguagem SQL, além de permitir a criação de Bancos de Dados e a sua gestão, também permite gerar esses insights. Em poucos minutos é possível gerar o material necessário para aquela reuinião urgente. A ideia é apresentar o uso de funções importantes como: SUM, GROUPBY, WHERE, JOIN e OVER em situações cotidianas, onde é possivel explorar o banco de dados de forma prática.

- Nesse case, temos um banco de dados de uma varejista com lojas, região de atuação etc e também temos uma tabela fato para todas as vendas, com informações de marca, produto, receita e diversos dados.

**A questão é: Como usar esses dados e gerar informações sobre o negócio em poucas linhas de código?**

- Descobrir quanto cada loja representa das vendas e rankear
Aqui é usada a famosa window function para conseguir fazer a divisão da quantidade vendida de cada loja, pela quantidade total *SUM('Qtd_Vendida')*, como não precisamos de dados de nenhuma outra tabela, o código dessa query é bem direto ao ponto.

<p align="center">
  <img alt="Code" width="60%" src="https://github.com/treeevisan/Portfolio/assets/152438468/62365c14-bc94-41ec-97cb-d52253c033f4">
  
</p>

Se fosse necessário utilizar essa informação em um dashboard, seria necessário criar uma view para ter informação pronta para ser importada em um software de BI.

- Descobrir dentro de uma marca de produto o faturamento
Agora a situação é um pouco mais complicada, pois os dados estão em tabelas diferentes. Vamos utilizar o conceito de banco de dados relacional aqui para conectar tabelas fato e dimensão para criar a query.


<p align="center">
  <img alt="Code" width="80%" src="https://github.com/treeevisan/Portfolio/assets/152438468/940da59c-8d1f-45f0-a94e-5b6dbce8a89c">
  
</p>

Com essa query podemos explorar a receita dos produtos de qualquer marca e identificar se existe um produto que é o carro chefe. 
Asism é possivel construir uma estratégia de preço com essas informações associadas a informações de quantidade vendida e estoque, aumentando a margem para itens que vendem bem e ajustando para itens que podem estar encalhados no estoque e precisam ser vendidos.


## **AUTOMAÇÕES** 

O bot foi feito para uma empresa norte americana com o objetivo de raspar os dados de um site que roda HTML com JavaScript. A automação foi construida em Selenium, pois apesar de mais lento em relação ao BeautifulSoup e Scrapy, ele permite criar requests em JavaScript e interagir online com servidor. Além do JavaScript, outro desafio do projeto é lidar com a falta de padronização dos dados no site, para isso foi fundamental o uso dos statements try e except na busca de elementos e validação de dados.

Seu output é um arquivo JSON, mas para melhor utilização do usuário final o bot gera um arquivo CSV 

<p align="center">
  <img alt="Code" width="70%" src="https://github.com/treeevisan/Portfolio/assets/152438468/be80f4aa-3583-4028-9d3c-a8849493e9c8">
  
</p>


<!--
## **AUTOMAÇÕES** - Em Breve
-->



## **SOBRE**

Seja bem-vindo(a)! Me chamo Renan.

Sou formado em Engenharia de Bioprocessos e Biotecnologia pela UFPR. Ao longo da graduação realizei diversas atividades que me proporcionaram desenvolver habilidades analíticas.

Minha trajetória profissional começou na gigante do automobilismo francês, Renault, onde pude aplicar meu aprendizado de engenharia e as habilidades desenvolvidas na graduação. Na sequência, trabalhei no banco Santander onde tive a oportunidade de conectar minha facilidade com dados e impactar a vida de milhares de pessoas. Ao longo dessa trajetória pratiquei constantemente o inglês e tive bastante contato com espanhol e francês.

Desde a graduação tenho aplicado meus conhecimentos em Excel e Power BI. Além disso, tenho construido projetos relacionados a análise de dados, web scraping. Nesse ambiente dos dados também possuo conhecimento em SQL, domino e pratico principalmente a linguagem Python, com projetos usando bibliotecas como Pandas, Numpy, Seaborn, Matplotlib e Plotly. 

Hoje estudo para estar em um ambiente data driven e expandir meus horizontes dentro desse universo. Quero aproveitar o conhecimento das pessoas mais experientes e levar novso insights.

## **CONTATO**
- [Linkedin](https://www.linkedin.com/in/renantrevisan/)
- [Kaggle](https://www.kaggle.com/renantrevisan)
  
