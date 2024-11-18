# Relatório Técnico: Implementação e Análise do Algoritmo de Regressão Linear



# Descrição	

O projeto é a resolução do desafio da unidade 9 para Residência de TIC oferecida pela CEPEDI. O projeto é implementação, estudo e análise de Regressão Linear e seus modelos de ajustes tomando como exemplo a base dados dos [Lista dos maiores influenciadores do instagram](https://www.kaggle.com/datasets/surajjha101/top-instagram-influencers-data-cleaned). 

O objetivo deste projeto é desenvolver um modelo preditivo usando o algoritmo de  **Regressão Linear**  para resolver um problema de  **inferência sobre taxa de engajamento**  dos principais influenciadores do instagram. O projeto envolve desde a análise exploratória dos dados até a otimização e validação do modelo. Trabalharemos para gerar inteligência para dois públicos: empresas e influenciadores.

Ao entender quais fatores influenciam a taxa de engajamento, as  **empresas**  podem escolher os influenciadores mais adequados para suas campanhas e alocar o orçamento de forma mais eficiente.

Ao identificar os principais determinantes da taxa de engajamento, os  **influenciadores**  podem otimizar suas estratégias de conteúdo e aumentar seu alcance e influência.

----------

**Variáveis originais**

**rank**: Definição: A posição do influenciador em um ranking, geralmente baseado no número de seguidores, engajamento ou influência geral. Um número menor indica maior influência.

**influence_score**: Definição: Uma métrica que avalia a influência geral do influenciador. Esse escore pode levar em conta vários fatores, como número de seguidores, taxa de engajamento e outros indicadores de popularidade ou impacto nas redes sociais.

**posts**: Definição: O número total de publicações feitas pelo influenciador na plataforma Instagram. Quanto maior o número de posts, maior a visibilidade do influenciador.

**followers**: Definição: O número total de seguidores do influenciador no Instagram. É uma métrica fundamental para entender o alcance de suas publicações.

**avg_likes**: Definição: O número médio de "curtidas" que o influenciador recebe por postagem. Essa variável pode indicar o nível de engajamento que as publicações estão gerando entre seus seguidores.

**60_day_eng_rate**: Definição: A taxa de engajamento dos últimos 60 dias. Normalmente, é calculada como a média de interações (curtidas, comentários, etc.) em relação ao número de seguidores, mostrando o engajamento relativo do público com as postagens recentes do influenciador.

**new_post_avg_like**: Definição: A média de "curtidas" recebidas nas postagens mais recentes do influenciador, ou seja, a média de curtidas nas publicações feitas mais recentemente (provavelmente uma média das últimas postagens).

**total_likes**: Definição: O número total de "curtidas" recebidas pelo influenciador em todas as suas postagens. Essa métrica dá uma ideia do impacto geral das publicações do influenciador ao longo do tempo.

**Variáveis derivadas**

**likes_per_follower**: Definição: A quantidade de "curtidas" que o influenciador recebe por seguidor. Essa métrica é uma maneira de avaliar a intensidade do engajamento em relação ao número de seguidores, mostrando quanto cada seguidor, em média, interage com as postagens.

**likes_per_post**: Definição: A média de "curtidas" que o influenciador recebe por postagem. Esse valor ajuda a entender o engajamento por postagem e é uma métrica importante para avaliar o desempenho de um influenciador, considerando o número de postagens realizadas.



## Instalação e Execução

Para instalação e verificação do código ( que foi feito em Google Colab), faça um git clone:
 git clone https://github.com/FelipeGas/Projeto.Reg.T3

Importe para o Google Colab (recomendado e melhor visualizado) ou use Jupyter Notebook e execute cada célula e leia atentamente os comentários, explicações e os gráficos correspondentes.

## Estrutura de arquivos

README.md
Relatório Técnico - Felipe Amorim & Caio Costa
Regressao_Linear_Influenciadores.ipynb


## Tecnologias Utilizadas

Google Colab 🙂
Python 
Pandas
Numpy
Statsmodels
Seaborn
Scipy
Scikit-Learn
Matplotlib

**Autores e Colaboradores**
Caio Costa Cavalcante
Felipe Gustavo Amorim Santos
