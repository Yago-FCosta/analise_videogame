# Análise Vendas Videogames

## Descrição do Projeto
Este projeto tem como objetivo analisar os dados de vendas de videogames de uma loja fictícia que vende no mundo todo.
As avaliações de usuários e especialistas, gêneros, plataformas (por exemplo, Xbox ou PlayStation) e dados históricos sobre vendas de jogos estão disponíveis em fontes abertas. 

**Contexto:** Vou identificar padrões que determinam se um jogo tem sucesso ou não. Isso vai permitir a identificação de possíveis sucessos e planejamento de campanhas publicitárias.
Os dados disponibilizados remontam a 2016. Esse estudo será realizado em dezembro de 2016 e estamos planejando uma campanha para 2017.

## Ferramentas e Bibliotecas Utilizadas
- Python: Linguagem principal utilizada para a análise.
- Pandas: Biblioteca para manipulação e análise de dados.
- Numpy e scipy: Biblioteca que visa possibilitar a computação numérica com Python 
- Matplotlib.pyplot e seaborn: Bibliotecas para criação de gráficos.

## Tabela
- Name (nome)
- Platform (plataforma)
- Year_of_Release (Ano de lançamento)
- Genre (gênero)
- NA_sales (vendas norte-americanas em milhões de USD)
- EU_sales (vendas na Europa em milhões de USD)
- JP_sales (vendas no Japão em milhões de USD)
- Other_sales (vendas em outros países em em milhões de USD)
- Critic_Score (Pontuação crítica) (máximo de 100)
- User_Score (Pontuação do usuário) (máximo de 10)
- Rating (classificação)

## Metodologia
**Análise Exploratória de Dados**
- Importar as bibliotecas necessárias
- Carregar e visualizar os dados

**Pré-processamento***
- Identificar e tratar valores ausentes
- Renomear colunas para nomes intuitivos e padronizados
- Corrigir valores anômalos
- Remover valores duplicados

**Análise dos Dados**
- Verificando quantos jogos foram lançados por ano
- Variação de vendas por plataforma
    - Geral
    - Rating
    - Região
- Analisando vendas por genre
    - Global
    - Regiões
**Criando e Validando Hipóteses**
- As classificações médias dos usuários das plataformas Xbox One e PC são as mesmas
- As classificações médias de usuários para os gêneros Action (ação) e Sports (esportes) são diferentes

## Resultados
Levando em conta que o estudo é para ajudar a determinar o lançamento de um próximo jogo, fizemos diversos estudos e análises sobre regiões, vendas, plataformas e generos.
Com isso o que estudamos, para o jogo ter sucesso, podemos focar na região NA que possui números mais expressivos de vendas, em comparação com o restante das regiões.
Pensando nela, sugiro que as 05 plataformas mais ápitas para o jogo são:
PS3, X360, PS4, 3DS e WII.
Acredito que o foco seje no PS4, pois é um plataforma nova (em relação as outras) e que já vem performando muito bem.

Em relação ao genero, os mais vendidos mundialmente e que atendem a todas as regiões são:
Action, Shooter, Sports, Role-Playing, Music
Com a preferência de vendas sendo jogos de ação (action).
