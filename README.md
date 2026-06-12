Descrição:
Trabalho de análise de dados em Python investigando a relação entre afiliação religiosa, escolaridade e renda no Brasil, com microdados dos Censos Demográficos do IBGE (1991, 2000 e 2010).

Estrutura:
01_coleta.ipynb — download automatizado dos microdados (FTP do IBGE)
02_limpeza.ipynb — leitura, classificação religiosa e harmonização dos 3 censos
03_analise.ipynb — coortes sintéticas, análises descritivas e gráficos interativos
04_regressao.ipynb — regressões OLS e logística

Dados
Os microdados brutos do IBGE não estão no repositório. 
o notebook 01_coleta.ipynb os baixa automaticamente do FTP público do IBGE.
O arquivo censo_religiao_renda.csv contém a base processada final 
(410 mil registros) usada nas análises dos notebooks 03 e 04.

Principais achados
Controlando demografia, a religião tem efeito pequeno sobre a renda direta
O efeito forte é indireto: a religião de berço associa-se à chance de diploma (OR pentecostal = 0,45; espírita = 4,78, vs. católicos)
Amostra: ~410 mil registros, 27 UFs, 3 censos
