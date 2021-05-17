# Twitter_Network_Analytics - PT
### Um framework para análise de dados de redes sociais usando análises e medidas de redes complexas, além de análise de sentimentos.

O projeto (parte 1, de 3) está descrito em detalhes no [Medium](https://felipe-marcel-neves.medium.com/twitter-network-analytics-fcb01272e2fd)

Uma prévia do projeto foi apresentado no canal [EstaTiDados](https://www.youtube.com/watch?v=jAl-GvLnAiw&t=1s), do mestre Thiago Marques (Pregador de Gauss, Fisher, Bernoulli...)

Este projeto em particular foca na temática das eleições 2020, onde extraí cerca de 122 mil tweets durante o último mês das eleições. Seu objetivo é revelar quais são os usuários/sub-temas/hashtags com poder de influência e propagação de informações na rede, e no futuro vincular tais resultados com a análise de sentimentos. Em outros artigos sobre o projeto, irei procurar responder perguntas mais específicas e utilizar análises complementares.

**Metodologia** 
<br /> 
Na primeira parte do projeto, apresento o framework do trabalho, métodos de coleta de dados utilizados (através da API do Twitter), preparação e limpeza dos dados, uma análise exploratória de dados extensa, análise de sentimentos (machine learning) e análise de redes (três métricas de centralidade e uma de comunidade, para a interpretação de três tipos de redes).

<img src="https://miro.medium.com/max/1163/1*sr5O0iNHzajHfn4DgTXL1w.gif" width="640" height="480">
Exemplo de rede do projeto - Rede de Retweets 
<br />
Esse projeto possui os seguintes arquivos: 
- Twitter_data_collection.ipynb = Notebook sobre a extração dos dados
- Twitter_Preparação_dos dados_data_wrangling.ipynb = Notebook da preparação dos dados coletados
- TweetsNeutralHash.csv, TweetsNeutralNews.csv, TweetsWithTheme.csv, NoThemeTweets.csv =  arquivos csv usados para compor o modelo para a análise de sentimentos
- stopwords.txt =  stopwords usados no modelo e nos dados
- Machine_learning_model_political_theme.ipynb = Notebook com a construção do modelo de regressão logística usado para a análise de sentimentos
- Pipeline LR = arquivo pickle com o modelo gerado no notebook anterior
- twitter_data_eleicoes-2020.csv = arquivo csv com os dados coletados do twitter pré-preparados em um único arquivo/dados usados nas análises
- Twitter_analysis_(exploratory,_sentimental_and_networks).ipynb = Notebook das análises do arquivo  

# Twitter_Network_Analytics - EN
### A framework for data analysis of social networks using analysis and measurements of complex networks, as well as sentiment analysis. 

The project (part 1, of 3) is described in details no [Medium](https://felipe-marcel-neves.medium.com/twitter-network-analytics-fcb01272e2fd) (only in portuguese for now)

A previous version of the project was presented in the youtube channel [EstaTiDados](https://www.youtube.com/watch?v=jAl-GvLnAiw&t=1s) from Thiago Marques (Pregador de Gauss, Fisher, Bernoulli ...)

This particular project focuses on the theme of the brazilian elections of 2020, where I extracted about 122 thousand tweets during the last month of elections. Its objective is to reveal which users / sub-themes / hashtags have the power to influence and spread information in the network, and in the future I will try to link these results with sentiment analysis. In other articles about or project, I will try to answer more specific questions and use complementary analyzes.

**Methodology** 
<br /> 
In this first part of the article, the presentation of a framework, data collection methods, data preparation and wrangling, a deep exploratory data analysis, sentiment analysis (machine learning) and network analysis (three metrics of centrality of the community) were made.

<img src="https://miro.medium.com/max/1163/1*sr5O0iNHzajHfn4DgTXL1w.gif" width="640" height="480">
Example of a network from the project - Retweet Network

