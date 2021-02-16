Web scraping criado para retirar dados da área de segurança do site: http://www.ssp.sp.gov.br/estatistica/pesquisa.aspx, o web scraping foi criado com python e ajuda
do biblioteca selenium e pandas, onde pego todos dados do estado de São Paulo e salvo num arquivo CSV, foi criado diversos if pois dependendo do ano determinado dado
da tabela era removido ou alterado de nome, e para conseguir criar um DataFrame é preciso que a quantidade de dados em cada vetor esteja igual então quando determinado
dado está em falta eu adiciono no vetor “dado faltante”. 
