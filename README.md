# Projeto - Tópicos Especiais em Métodos Quantitativos

## Autoria 
- Gabrielle Carvalho
- Ingrid de Sales Rabelo
- Maria Isabel Souza
- Laura Maranhão Fernandes

## Objetivo Geral
O projeto foi elaborado para a cadeira de Tópicos Especiais em Métodos Quantitativos 2021.2 UFPE - PIMES, e consiste na coleta, tratamento, análise e produção de previsões sobre os ganhadores das partidas dos jogos da Copa do Mundo de Futebol Feminino - FIFA. O campeonato deu-se início  em 1991. Desde então já ocorreram 8 edições,  nas quais se disputaram 284 partidas, com 36 seleções distintas participantes.

## Organização do projeto
O projeto está organizado em quatro etapas, são elas:
 - A coleta dos dados, incluindo todas as partidas durante os anos, via _web scraping_, no site oficial da [FIFA](https://www.fifa.com/fifaplus/en/tournaments/womens/womensworldcup/); 
 - O tratamento de dados, que consiste em gerar percentuais de desempenho e em organizar os inputs em uma nova tabela; 
 - A análise, que consiste na produção de visualizações dos dados;
 - A previsão, utilizando-se do método de _Deep Learning_.

 No repositório apresentamos 3 pastas. Na primeira `código`, encontra-se os 4 códigos utilizados em cada etapa, sendo elas a `coleta_dados_fifa.ipynb`, `tratamento_tabela_fifa.ipynb`, `visualizacao_dados_fifa.ipynb`, e `deep_neural.ipynb`. Já na pasta `auxiliar`, temos a versão mais atualizada do _chromedriver_, necessária para a execução do _web scraping_. Por fim, a pasta `input` armazena os dados coletados e tratados.
 
## Como usar
Fazer o download deste repositório para sua máquina local e rodar os códigos, os caminhos dos arquivos já estão relativos.

## Bibliotecas Necessárias
- [selenium](https://pypi.org/project/selenium/)
- [bs4](https://pypi.org/project/bs4/)
- [requests](https://pypi.org/project/requests/)
- [pandas](https://pypi.org/project/pandas/)
- [random](https://docs.python.org/3/library/random.html)
- [pygal](https://pypi.org/project/pygal/)
- [sklearn](https://pypi.org/project/sklearn/)
- [geopandas](https://pypi.org/project/geopandas/)
- [numpy](https://pypi.org/project/numpy/)
- [folium](https://pypi.org/project/folium/)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [seaborn](https://pypi.org/project/seaborn/)
- [itertools](https://docs.python.org/3/library/itertools.html)
- [keras](https://pypi.org/project/keras/)
- [tensorflow](https://pypi.org/project/tensorflow/)


 
